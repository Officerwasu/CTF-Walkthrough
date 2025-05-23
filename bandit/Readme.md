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

The password for the next level can be retrieved by submitting the password of the current level to port 30001 on localhost using SSL/TLS encryption.

Helpful note: Getting “DONE”, “RENEGOTIATING” or “KEYUPDATE”? Read the “CONNECTED COMMANDS” section in the manpage.


#### Solution

![image](https://github.com/user-attachments/assets/d0ae94cb-49e4-4ec1-a4e2-8f56adce2fb5)


`kSkvUpMQ7lBYyCM4GBPvCvT1BfWRy0Dx`

## Level 16-17

#### Level Goal
The credentials for the next level can be retrieved by submitting the password of the current level to a port on localhost in the range 31000 to 32000. First find out which of these ports have a server listening on them. Then find out which of those speak SSL/TLS and which don’t. There is only 1 server that will give the next credentials, the others will simply send back to you whatever you send to it.

Helpful note: Getting “DONE”, “RENEGOTIATING” or “KEYUPDATE”? Read the “CONNECTED COMMANDS” section in the manpage.

#### Solution

![image](https://github.com/user-attachments/assets/5bfb9016-ba83-4c30-8dae-5855a203bc81)

![image](https://github.com/user-attachments/assets/6bdbca4f-efb0-474b-aed8-988cae8bc177)

![image](https://github.com/user-attachments/assets/caccacf7-8a36-41a8-903f-b90f81ada097)

![image](https://github.com/user-attachments/assets/b297e1ce-e896-4c7c-9de5-580f3ca3af15)

![image](https://github.com/user-attachments/assets/a52e8f2c-fe74-42f5-9e18-a0c929edfa0b)

![image](https://github.com/user-attachments/assets/bcb29d9d-9fdd-48e4-80af-27dd5703e856)

password `EReVavePLFHtFlFsjn3hyzMlvSuSAcRD`

## Level 17-18

#### Level Goal
There are 2 files in the homedirectory: passwords.old and passwords.new. The password for the next level is in passwords.new and is the only line that has been changed between passwords.old and passwords.new

NOTE: if you have solved this level and see ‘Byebye!’ when trying to log into bandit18, this is related to the next level, bandit19

#### Solution

![image](https://github.com/user-attachments/assets/40020e9f-ac26-4159-b771-a3aaaf76675b)

password `x2gLTTjFwMOhQ8oWNbMN362QKxfRqGlO`

## Level 18-19

#### Level Goal

The password for the next level is stored in a file readme in the homedirectory. Unfortunately, someone has modified .bashrc to log you out when you log in with SSH.

#### Solution 

![image](https://github.com/user-attachments/assets/8c6eb1cf-0b90-47d8-a1b1-e3b3895c5119)
![image](https://github.com/user-attachments/assets/929eea5e-d8f2-4a86-9234-31fbd74fda86)

password `cGWpMaKXVwDUNgPAVJbWYuGHVn9zl3j8`

## Level 19-20

#### Level Goal

To gain access to the next level, you should use the setuid binary in the homedirectory. Execute it without arguments to find out how to use it. The password for this level can be found in the usual place (/etc/bandit_pass), after you have used the setuid binary.

#### Solution
![image](https://github.com/user-attachments/assets/2ca5b82f-e6fd-4f1e-9652-b29bc06c57e1)

password `0qXahG8ZjOVMN9Ghs7iOWsCfZyXOUbYO`

## Level 20-21

#### Level Goal

There is a setuid binary in the homedirectory that does the following: it makes a connection to localhost on the port you specify as a commandline argument. It then reads a line of text from the connection and compares it to the password in the previous level (bandit20). If the password is correct, it will transmit the password for the next level (bandit21).

#### Solution

![image](https://github.com/user-attachments/assets/3d1b5c18-e9cd-496e-87eb-38c8482c9557)

password `EeoULMCra2q0dSkYj561DX7s1CpBuOBt`

## Level 21-22

#### Level Goal

A program is running automatically at regular intervals from cron, the time-based job scheduler. Look in /etc/cron.d/ for the configuration and see what command is being executed.

#### Solution

![image](https://github.com/user-attachments/assets/c1847c5a-4da3-49fd-afbf-2eeb47fda88a)

password `tRae0UfB9v0UzbCdn9cY0gQnds9GF58Q`

## Level 22-23

#### Level Goal

A program is running automatically at regular intervals from cron, the time-based job scheduler. Look in /etc/cron.d/ for the configuration and see what command is being executed.

NOTE: Looking at shell scripts written by other people is a very useful skill. The script for this level is intentionally made easy to read. If you are having problems understanding what it does, try executing it to see the debug information it prints.

#### Solution

![image](https://github.com/user-attachments/assets/87954502-dce6-4013-8b3b-0c9399ef2c0c)
![image](https://github.com/user-attachments/assets/96373026-7306-4767-93c7-3a762424e216)

password `0Zf11ioIjMVN551jX3CmStKLYqjk54Ga`


## Level 23-24

#### Level Goal

A program is running automatically at regular intervals from cron, the time-based job scheduler. Look in /etc/cron.d/ for the configuration and see what command is being executed.

NOTE: This level requires you to create your own first shell-script. This is a very big step and you should be proud of yourself when you beat this level!

NOTE 2: Keep in mind that your shell script is removed once executed, so you may want to keep a copy around…

#### Soution


![image](https://github.com/user-attachments/assets/4cfe28e2-c2b4-4def-8f92-af15353de363)
![image](https://github.com/user-attachments/assets/729879ef-074b-4f08-9da4-0f5c0f672aa0)
![image](https://github.com/user-attachments/assets/10b97f8d-aeae-4a6a-ba3d-ef9ea708c8bb)
![image](https://github.com/user-attachments/assets/06ef0eae-53ac-48ce-9679-9b827313fd25)

password `gb8KRRCsshuZXI0tUuR6ypOFjiZbf3G8`

## Level 24-25

#### Level Goal

A daemon is listening on port 30002 and will give you the password for bandit25 if given the password for bandit24 and a secret numeric 4-digit pincode. There is no way to retrieve the pincode except by going through all of the 10000 combinations, called brute-forcing.
You do not need to create new connections each time.

#### Solution

![image](https://github.com/user-attachments/assets/a6daf9bd-7293-45d9-9ac5-4de38b7746c2)
![image](https://github.com/user-attachments/assets/0fc66756-c05c-4751-8ae7-7f1a7006c366)
![image](https://github.com/user-attachments/assets/60ed9b1b-6d20-4bd2-af3f-c206bde33ba4)

password `iCi86ttT4KSNe1armKiwbQNmB3YJP3q4`

## Level 25-26

#### Level Goal

Logging in to bandit26 from bandit25 should be fairly easy… The shell for user bandit26 is not /bin/bash, but something else. Find out what it is, how it works and how to break out of it.

NOTE: if you’re a Windows user and typically use Powershell to ssh into bandit: Powershell is known to cause issues with the intended solution to this level. You should use command prompt instead.

#### Solution
okay so we got the ssh private key but it was not logging in bash insted it was laoding in somthing called showtext

![image](https://github.com/user-attachments/assets/69543b87-5985-4133-ad50-c6612863853c)

![image](https://github.com/user-attachments/assets/b7ef05a2-a3f4-444f-ae10-72005b19a6bc)

contents of text.txt

![image](https://github.com/user-attachments/assets/672dd679-4045-4c9e-ae2f-bbed6647a3a0)



it was using more 

in more

we use vi to execute `cat /etc/bandit_password/bandit26`

![image](https://github.com/user-attachments/assets/9f016aee-cb2f-4b7d-8ced-815a97c079e9)


password `s0773xxkk0MXfdqOfPRVr9L3jJBUOgCZ`


**Now accesesing this is really difficult** 
you will need to use vim inside of more and set the shell to /bin/bash after that you will be able to access it


## Level 26-27

#### Level Goal

Good job getting a shell! Now hurry and grab the password for bandit27!

#### Solution

![image](https://github.com/user-attachments/assets/1e30c67f-7a0f-468a-bad0-d4aaeab32e82)

password `upsNCc7vzaRDx6oZC6GiR6ERwe1MowGB`

## Level 27-28

#### Level Goal

There is a git repository at ssh://bandit27-git@localhost/home/bandit27-git/repo via the port 2220. The password for the user bandit27-git is the same as for the user bandit27.

Clone the repository and find the password for the next level.

#### Solution

Go to the temp folder and make a directory

![image](https://github.com/user-attachments/assets/a9b5771d-6f96-4deb-9755-49b0c77203f0)

![image](https://github.com/user-attachments/assets/1d854f47-9e1e-4c90-96ae-f96528434609)

password `Yz9IpL0sBcCeuG7m9uQFt8ZNpS4HZRcN`


## Level 28-29

#### Level Goal

There is a git repository at ssh://bandit28-git@localhost/home/bandit28-git/repo via the port 2220. The password for the user bandit28-git is the same as for the user bandit28.

Clone the repository and find the password for the next level.

#### Solution

![image](https://github.com/user-attachments/assets/c972b29d-382e-431f-992e-7af2df2c1f50)

![image](https://github.com/user-attachments/assets/a29366ef-18a7-42b6-9831-4065d6183ba3)


![image](https://github.com/user-attachments/assets/7aea08d0-09b8-4f6a-9a0a-f6dd3da7b16a)


password `4pT1t5DENaYuqnqvadYs1oE4QLCdjmJ7`

## Level 29-30

#### Level Goal

There is a git repository at ssh://bandit29-git@localhost/home/bandit29-git/repo via the port 2220. The password for the user bandit29-git is the same as for the user bandit29.

Clone the repository and find the password for the next level.


#### Solution

A first few steps are the same the only difference is you have to switch to the dev branch

![image](https://github.com/user-attachments/assets/c1527610-151f-411e-bf31-ac4c033d2e3d)

![image](https://github.com/user-attachments/assets/a389c6de-12ce-42a3-aea0-647491a98f85)

password `qp30ex3VLz5MDG1n91YowTv4Q8l7CDZL`

## Level 31-32

#### Level Goal

There is a git repository at ssh://bandit30-git@localhost/home/bandit30-git/repo via the port 2220. The password for the user bandit30-git is the same as for the user bandit30.

Clone the repository and find the password for the next level.

#### Solution

same as the earlier levels but the only change was it had a tag

![image](https://github.com/user-attachments/assets/edae32a2-23a6-45c2-80bc-e8ed657082c7)

password `fb5S2xb7bRyFmAvQYQGEqsbhVyJqhnDy`

