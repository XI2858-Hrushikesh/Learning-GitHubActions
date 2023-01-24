---
slug: first-shell-script-hello-world-shell-script
id: 2narprxkdxo0
type: challenge
title: First Shell Script - Hello World Shell Script
teaser: First Shell Script - Hello World Shell Script.
notes:
- type: text
  contents: Write your First Shell Script
tabs:
- title: Shell
  type: terminal
  hostname: myhost
  workdir: /
difficulty: basic
timelimit: 600
---
# Write your First Shell Script
Become a sudo user using:

```
sudo su
```

To create first shell script,
Use command:

```
vi first.sh
```

(you can use any extension for shell script however best practice is to use .sh extension)

new file named first.sh will open.

You can enter any data whichever you want.
Enter sample commands:

```
echo "this is my first shell script"
pwd
ls first.sh
ls -l first.sh
```

Then click

```
:wq
```
to save and overwright the changes in file.

You will be back on editor.

Check script file using

```
ls
```
Check file permission using

```
ls -l
```

By default file will not have execute permission.

So in order to run the script file, file need execute permission.

Change file permission using

```
chmod +x first.sh
```

(It will add execute permission)

Now run your first script using

```
./first.sh
```

