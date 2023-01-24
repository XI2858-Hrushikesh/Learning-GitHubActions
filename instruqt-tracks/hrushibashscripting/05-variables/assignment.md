---
slug: variables
id: jkvmfvueph9u
type: challenge
title: Variables
teaser: User Defined Variables.
notes:
- type: text
  contents: Variables
tabs:
- title: Shell
  type: terminal
  hostname: myhost
  workdir: /
difficulty: basic
timelimit: 600
---
# Variables

Open file created "first.sh" in last challenge:

```
sudo su
vi first.sh
```



Declare variables and use as:

```
name="Hrushikesh"
age="35"
action="check"
what="slack"
```
Use variables using echo command:
# Way1

```
echo "My name is $name and I am $age years old"
```

# Way 2

```
echo "My name is ${name} and I am ${age} years old"
```
# Way 3

```
echo "What should I do?"
echo "please ${action} ${what}"
```


# variable name rules:

- variable name should be alphanumeric.
- you can use _ anywhere even at the start.
- Variable name can not start with a number.
- variable name can not be reserved words
- variable name can not have white space in between
- variable name can not have special characters

------------------------------------------------------------------------------------------------------------


