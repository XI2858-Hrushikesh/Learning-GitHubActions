---
slug: shebang-shell-script
id: kn4yymtnxjz0
type: challenge
title: Shebang Shell Script
teaser: Shebang Shell Script.
notes:
- type: text
  contents: Shebang Shell Script
tabs:
- title: Shell
  type: terminal
  hostname: myhost
  workdir: /
difficulty: basic
timelimit: 600
---
# Shebang Shell Script
The #! syntax is used in scripts to indicate an interpreter for execution under UNIX / Linux operating systems. The directive must be the first line in the Linux shell script and must start with shebang #!. You can add argument after the shebang characters, which is optional. Make sure the interpreter is the full path to a binary file. For example: /bin/bash.

- First line (#!) is called a shebang or a "bang" line.
- It is nothing but the absolute path to the Bash interpreter.
- It consists of a number sign and an exclamation point character (#!), followed by the full path to the interpreter such as /bin/bash.
- Almost all bash scripts often begin with #!/bin/bash

Example:
Most Linux shell and perl / python script starts with the following line. Bash or sh example:
```
#!/bin/bash
```

OR
```
#!/usr/bin/env bash
```
Benefits:

- It makes shell scripts more like actual executable files, because they can be the subject of 'exec.'
- If you do a 'ps -ef' while such a command is running, the real name appears instead of 'sh' or 'bash'. Likewise, system accounting is done based on the real name.

Open file created "first.sh" in last challenge:

```
sudo su
vi first.sh
```

and now add shebang:

```
#!/bin/bash
```
```
:wq
```
now run your bash script again:
```
./first.sh
```