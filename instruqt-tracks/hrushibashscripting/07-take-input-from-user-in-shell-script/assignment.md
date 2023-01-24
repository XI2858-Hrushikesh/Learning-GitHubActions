---
slug: take-input-from-user-in-shell-script
id: kpweyjzkkwdj
type: challenge
title: Take Input From User in Shell Script
teaser: Take Input From User in Shell Script.
notes:
- type: text
  contents: Take Input From User in Shell Script
tabs:
- title: Shell
  type: terminal
  hostname: myhost
  workdir: /
difficulty: basic
timelimit: 600
---
#Let's learn how to Take Input From User in Shell Script

```read``` command is used to take run-time input from user.

Open file created "first.sh" in last challenge:

```
sudo su
vi first.sh
```

```
read name
read age

echo "Your name is ${name} and you are ${age} years old"
```

In case if you miss to add variable name with ```read```, it will not print the value however the value will be stored in system variable named: ```REPLAY```

