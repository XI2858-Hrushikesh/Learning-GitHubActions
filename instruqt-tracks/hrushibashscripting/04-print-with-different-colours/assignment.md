---
slug: print-with-different-colours
id: p5v2qygrv9si
type: challenge
title: print with different colours
teaser: A short description of the challenge.
notes:
- type: text
  contents: print with different colours
tabs:
- title: Shell
  type: terminal
  hostname: myhost
  workdir: /
difficulty: basic
timelimit: 600
---
# print with different colours

Open file created "first.sh" in last challenge:

```
sudo su
vi first.sh
```

You can use echo command with single quotes/double quotes or without quotes as well.

Example with differance:
```
echo this is demo
```
This will print the message : this is demo

```
echo this is                 demo
```
This will also print the message : this is demo so here the extra space will be removed.

```
echo 'this is                 demo'
```

```
echo "this is                 demo"
```

So if you need extra space or print the text as it is, you need to use single/double quotes.

Single quote is also called Strong quote as it will print everything as it is.

Here we are using echo -e command to enable interpretation of backslash escapes

```
echo -e "\033[0;31m You lost"
echo -e "\033[0;32m You win"
echo -e "\033[0;33m Better luck next time"
```

This will print the text messages in Orange, Green, Red colour respectively. You need to remember the colour codes.

You print add multi-lined text:

```
echo "
This
is
my
testing
script
"
```
If your next line is part of first line you can add "\" after every line.
Example:
```
echo "This \
is \
my \
testing \
script \
"
```
# this feature can be used if you need to install multiple packages

# Use # to comment any line
