---
slug: system-defined-variables
id: gpxui7jgdmzl
type: challenge
title: System Defined Variables
teaser: System Defined Variables.
notes:
- type: text
  contents: System Defined Variables
tabs:
- title: Shell
  type: terminal
  hostname: myhost
  workdir: /
difficulty: basic
timelimit: 600
---
# System Defined Variables. Ususlly System defined variables are Read-only so you can not change their values.

Below are some System defined Variables:
```
echo ${SHELL}
```
# Above command returns the shell which you are using.
```
echo ${HOME}
```
# Above command returns root diroctory.
```
echo ${OSTYPE}
```
# Above command returns type of Operating System used.
```
echo ${$}
```
# Above command returns process ID
```
echo ${PPID}
```
# Above command returns parent process ID
```
echo ${PWD}
```
# Above command returns Present Working Directory
```
echo ${HOSTNAME}
```
# Above command returns Host Name
```
echo ${UID}
```
# Above command returns User ID (UID for root user is always 0)
```
echo ${SECONDS}
```
# Above command returns seconds required to complete a script.

To see more System Defined commands, you can check:
```
man bash
```
Scroll down till "Shell Variables"
