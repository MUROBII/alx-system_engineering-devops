<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
</head>
<body>

# Regular Expressions Project

This repository contains a collection of Ruby scripts that demonstrate the usage of regular expressions to match specific patterns. Each script addresses a particular requirement and includes a corresponding test case.

## Table of Contents

1. [Simply matching School](#simply-matching-school)
2. [Repetition Token #0](#repetition-token-0)
3. [Repetition Token #1](#repetition-token-1)
4. [Repetition Token #2](#repetition-token-2)
5. [Repetition Token #3](#repetition-token-3)
6. [Not quite HBTN yet](#not-quite-hbtn-yet)
7. [Call me maybe](#call-me-maybe)
8. [OMG WHY ARE YOU SHOUTING?](#omg-why-are-you-shouting)
9. [Textme](#textme)

## Simply matching School


**Requirements:**
- The regular expression must match `School`.
- Using the project instructions, create a Ruby script that accepts one argument and passes it to a regular expression matching method.

**Conceptual Description:**
![Simply matching School](https://example.com/simply_matching_school_image.png)

**Example:**
```
./0-simply_match_school.rb School | cat -e
School$
./0-simply_match_school.rb "Best School" | cat -e
School$
./0-simply_match_school.rb "School Best School" | cat -e
SchoolSchool$
./0-simply_match_school.rb "Grace Hopper" | cat -e
$
```

**Repo:**
- GitHub repository: [alx-system_engineering-devops](https://github.com/MUROBII/alx-system_engineering-devops)
- Directory: 0x06-regular_expressions
- File: 0-simply_match_school.rb

## Repetition Token #0


**Requirements:**
- Find the regular expression that will match the above cases.
- Using the project instructions, create a Ruby script that accepts one argument and passes it to a regular expression matching method.

**Conceptual Description:**
![Repetition Token #0](./task0)
<img src="./task0">

**Example:**
```
./1-repetition_token_0.rb | cat -e
$
```

**Repo:**
- GitHub repository: [alx-system_engineering-devops](https://github.com/MUROBII/alx-system_engineering-devops)
**Score:** 0.0%
- Directory: 0x06-regular_expressions
- File: 1-repetition_token_0.rb

## Repetition Token #1


**Requirements:**
- Find the regular expression that will match the above cases.
- Using the project instructions, create a Ruby script that accepts one argument and passes it to a regular expression matching method.

**Conceptual Description:**
![Repetition Token #1](./task1)
<img src="./task1">

**Example:**
```
./2-repetition_token_1.rb | cat -e
$
```

**Repo:**
- GitHub repository: [alx-system_engineering-devops](https://github.com/MUROBII/alx-system_engineering-devops)
- Directory: 0x06-regular_expressions
- File: 2-repetition_token_1.rb

## Repetition Token #2


**Requirements:**
- Find the regular expression that will match the above cases.
- Using the project instructions, create a Ruby script that accepts one argument and passes it to a regular expression matching method.

**Conceptual Description:**
![Repetition Token #2](./task2)
<img src="./task2">

**Example:**
```
./3-repetition_token_2.rb | cat -e
$
```

**Repo:**
- GitHub repository: [alx-system_engineering-devops](https://github.com/MUROBII/alx-system_engineering-devops)
- Directory: 0x06-regular_expressions
- File: 3-repetition_token_2.rb

## Repetition Token #3


**Requirements:**
- Find the regular expression that will match the above cases.
- Using the project instructions, create a Ruby script that accepts one argument and passes it to a regular expression matching method.
- Your regex should not contain square brackets.

**Conceptual Description:**
![Repetition Token #3](./tastk3)
<img src="./task3">

**Example:**
```
./4-repetition_token_3.rb | cat -e
$
```

**Repo:**
- GitHub repository: [alx-system_engineering-devops](https://github.com/MUROBII/alx-system_engineering-devops)
- Directory: 0x06-regular_expressions
- File: 4-repetition_token_3.rb

## Not quite HBTN yet


**Requirements:**
- The regular expression must be exactly matching a string that starts with `h`, ends with `n`, and can have any single character in between.
- Using the project instructions, create a Ruby script that accepts one argument and passes it to a regular expression matching method.

**Conceptual Description:**
![Not quite HBTN yet](./task4)
<img src="./task4">

**Example:**
```
./5-beginning_and_end.rb 'hn' | cat -e
$
./5-beginning_and_end.rb 'hbn' | cat -e
hbn$
./5-beginning_and_end.rb 'hbtn' | cat -e
$
./5-beginning_and_end.rb 'h8n' | cat -e
h8n$
```

**Repo:**
- GitHub repository: [alx-system_engineering-devops](https://github.com/MUROBII/alx-system_engineering-devops)
- Directory: 0x06-regular_expressions
- File: 5-beginning_and_end.rb

## Call me maybe


**Requirements:**
- The regular expression must match a 10-digit phone number.
- Using the project instructions, create a Ruby script that accepts one argument and passes it to a regular expression matching method.

**Conceptual Description:**
![Call me maybe](./task5)
<img src="./task5">

**Example:**
```
./6-phone_number.rb 4155049898 | cat -e
4155049898$
./6-phone_number.rb " 4155049898" | cat -e
$
./6-phone_number.rb "415 504 9898" | cat -e
$
./6-phone_number.rb "415-504-9898" | cat -e
$
```

**Repo:**
- GitHub repository: [alx-system_engineering-devops](https://github.com/MUROBII/alx-system_engineering-devops)
- Directory: 0x06-regular_expressions
- File: 6-phone_number.rb

## OMG WHY ARE YOU SHOUTING?


**Requirements:**
- The regular expression must only match capital letters.

- Using the project instructions, create a Ruby script that accepts one argument and passes it to a regular expression matching method.

**Conceptual Description:**
![OMG WHY ARE YOU SHOUTING?](./task6)
<img src="./task6">

**Example:**
```
./7-OMG_WHY_ARE_YOU_SHOUTING.rb "I realLy hOpe VancouvEr posseSs Yummy Soft vAnilla Dupper Mint Ice Nutella cream" | cat -e
ILOVESYSADMIN$
./7-OMG_WHY_ARE_YOU_SHOUTING.rb "WHAT do you SAY?" | cat -e
WHATSAY$
./7-OMG_WHY_ARE_YOU_SHOUTING.rb "cannot read you" | cat -e
$
```

**Repo:**
- GitHub repository: [alx-system_engineering-devops](https://github.com/MUROBII/alx-system_engineering-devops)
- Directory: 0x06-regular_expressions
- File: 7-OMG_WHY_ARE_YOU_SHOUTING.rb

## Textme


**Requirements:**
- Your script should output: `[SENDER],[RECEIVER],[FLAGS]`
- The sender phone number or name (including country code if present)
- The receiver phone number or name (including country code if present)
- The flags that were used
- Using the project instructions, create a Ruby script that accepts one argument and passes it to a regular expression matching method.

**Conceptual Description:**
![Textme](./task7)
<img src="./task7">

**Example:**
```
./100-textme.rb 'Feb 1 11:00:00 ip-10-0-0-11 mdr: 2016-02-01 11:00:00 Receive SMS [SMSC:SYBASE1] [SVC:] [ACT:] [BINF:] [FID:] [from:Google] [to:+16474951758] [flags:-1:0:-1:0:-1] [msg:127:This planet has - or rather had - a problem, which was this: most of the people on it were unhappy for pretty much of the time.] [udh:0:]'
Google,+16474951758,-1:0:-1:0:-1
```

**Repo:**
- GitHub repository: [alx-system_engineering-devops](https://github.com/MUROBII/alx-system_engineering-devops)
- Directory: 0x06-regular_expressions
- File: 100-textme.rb

</body>
</html>
