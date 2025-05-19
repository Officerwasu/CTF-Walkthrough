# Bandit 
## Level 0

#### Level Goal

The goal of this level is for you to log into the game using SSH. The host to which you need to connect is bandit.labs.overthewire.org, on port 2220. The username is bandit0 and the password is bandit0. Once logged in, go to the Level 1 page to find out how to beat Level 1.

#### Solution

`ssh bandit0@bandit.labs.overthewire.org -p 2220`

and put in the password `bandit0`

## Level 0-1

#### Level Goal

The password for the next level is stored in a file called readme located in the home directory. Use this password to log into bandit1 using SSH. Whenever you find a password for a level, use SSH (on port 2220) to log into that level and continue the game.

#### Solution

![image](https://github.com/user-attachments/assets/cb1e1d0f-64c9-4466-b5e1-66caad3e6beb)

password is `ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If`

**Now login to bandit1 with this password using ssh**

## Level 1-2

#### Level Goal

The password for the next level is stored in a file called - located in the home directory

#### Solution

![image](https://github.com/user-attachments/assets/b4aa8fdc-e742-40f2-a8c1-941484134ee0)

password is `263JGJPfgU6LtdEvgfWU1XP5yac29mFx`

## Level 2-3

#### Level Goal

The password for the next level is stored in a file called spaces in this filename located in the home directory

#### Solution

![image](https://github.com/user-attachments/assets/3aa3931c-7ae2-404f-9685-a8ea9c6eda9d)

password is `MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx`

## Level 3-4

#### Level Goal

The password for the next level is stored in a hidden file in the inhere directory.

#### Solution

![image](https://github.com/user-attachments/assets/4942deb6-b965-40c8-ae29-dd9b3b6e5292)

password is `2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ`

## Level 4-5

#### Level Goal

The password for the next level is stored in the only human-readable file in the inhere directory. Tip: if your terminal is messed up, try the “reset” command.

#### Solution

![image](https://github.com/user-attachments/assets/9156bd1b-39a0-47a2-bcd1-b43a00306190)

password is `4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw`

## Level 5-6

#### Level Goal
The password for the next level is stored in a file somewhere under the inhere directory and has all of the following properties:

human-readable
1033 bytes in size
not executable

#### Solution

![image](https://github.com/user-attachments/assets/2bac2688-11c9-4b93-9853-c85f18e8a8d9)

password is `HWasnPhtq9AVKe0dmk45nxy20cvUa6EG`

## Level 6-7

#### Level Goal

The password for the next level is stored somewhere on the server and has all of the following properties:

owned by user bandit7
owned by group bandit6
33 bytes in size

#### Solution 

![image](https://github.com/user-attachments/assets/868442a5-2ed1-4f60-920b-7ffaf26f3ead)

password `morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj`

## Level 7-8

#### Level Goal

The password for the next level is stored in the file data.txt next to the word millionth

#### Solution

![image](https://github.com/user-attachments/assets/72ce5f5b-51c0-4781-afba-3492cde886d2)

password `dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc`

## Level 8-9

#### Level Goal

The password for the next level is stored in the file data.txt and is the only line of text that occurs only once

#### Solution 

![image](https://github.com/user-attachments/assets/30b79f81-fa35-468a-8e81-175b7659d6c7)

password `4CKMh1JI91bUIZZPXDqGanal4xvAg0JM`

## Level 9-10

#### Level Goal

The password for the next level is stored in the file data.txt in one of the few human-readable strings, preceded by several ‘=’ characters.

#### Solution

![image](https://github.com/user-attachments/assets/d4998fd5-68ed-45e7-9b71-4f79a4ed9a08)

password `FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey`

## Level 10-11

#### Level Goal

The password for the next level is stored in the file data.txt, which contains base64 encoded data

#### Solution

![image](https://github.com/user-attachments/assets/a5597cf4-0bae-4241-8c3f-ac665413c01a)

password is `dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr`

## Level 11-12

#### Level Goal

The password for the next level is stored in the file data.txt, where all lowercase (a-z) and uppercase (A-Z) letters have been rotated by 13 positions.

#### Solution

![image](https://github.com/user-attachments/assets/50f3aa37-6bb5-4cc0-bfbd-93b38ee1e717)

password `7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4`

## Level 12-13

#### Level Goal

The password for the next level is stored in the file data.txt, which is a hexdump of a file that has been repeatedly compressed. For this level it may be useful to create a directory under /tmp in which you can work. Use mkdir with a hard to guess directory name. Or better, use the command “mktemp -d”. Then copy the datafile using cp, and rename it using mv (read the manpages!)

#### Solution

okay that was really difficult 😭
This wlll need a complete guide

![image](https://github.com/user-attachments/assets/335a04f7-35ee-42e4-9bed-b0bffcdfd282)

![image](https://github.com/user-attachments/assets/018184cd-e3f0-4220-8e64-668d27d11255)

![image](https://github.com/user-attachments/assets/988d699a-9004-42cf-8ccd-54f4f8c832d8)

![image](https://github.com/user-attachments/assets/ec1acd64-c915-4e69-bbb5-30113fb04ccf)

![image](https://github.com/user-attachments/assets/db72dbc4-f7e4-41bc-9e81-c37c5eafa9e8)

![image](https://github.com/user-attachments/assets/cd18ba8b-8294-40ef-85cd-a23926bcef3d)



password `FO5dwFsc0cbaIiH0h8J2eUks2vdTDwAn`

## Level 13-14

#### Level Goal

The password for the next level is stored in /etc/bandit_pass/bandit14 and can only be read by user bandit14. For this level, you don’t get the next password, but you get a private SSH key that can be used to log into the next level. Note: localhost is a hostname that refers to the machine you are working on

#### Solution

![image](https://github.com/user-attachments/assets/97067dfc-63c8-496b-afed-94c0e115596d)

![image](https://github.com/user-attachments/assets/bbebdda5-1111-49ce-868b-345184212a1e)

passowrd `MU4VWeTyJk8ROof1qqmcBPaLh7lDCPvS`

## Level 14-15

#### Level Goal

The password for the next level can be retrieved by submitting the password of the current level to port 30000 on localhost.

#### Solution


![image](https://github.com/user-attachments/assets/bf0fb657-b62b-4c85-8eb3-5a04f0e42b39)

password `8xCjnmgoKbGLhHFAZlGE5Tmu4M2tKJQo`

## Level 15-16

#### Level Goal





