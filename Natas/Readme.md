## Natas

#### Natas teaches the basics of serverside web-security.

Each level of natas consists of its own website located at http://natasX.natas.labs.overthewire.org, where X is the level number. There is no SSH login. To access a level, enter the username for that level (e.g. natas0 for level 0) and its password.

Each level has access to the password of the next level. Your job is to somehow obtain that next password and level up. All passwords are also stored in /etc/natas_webpass/. E.g. the password for natas5 is stored in the file /etc/natas_webpass/natas5 and only readable by natas4 and natas5.

Start here:

Username: natas0

Password: natas0

URL:      http://natas0.natas.labs.overthewire.org



## Natas 0

Just view page source and you'll be able to see the password

![image](https://github.com/user-attachments/assets/8142c32c-8528-4f59-89ab-c2a3112e84ab)

password `0nzCigAq7t2iALyvU9xcHlYN4MlkIwlq `

## Natas 0-1

Just use ctrl+shift+i to inspect
![image](https://github.com/user-attachments/assets/e6ac6545-895f-4889-bd3f-896cb86afe3e)

password `TguMNxKo1DSa1tujBLuZJnDUlCcUAPlI`

## Natas 1-2

![image](https://github.com/user-attachments/assets/fcad5295-c447-4102-a9c1-1d0445369e7d)

![image](https://github.com/user-attachments/assets/1be0f6a2-f9a6-4386-a823-6b5ea2dfa471)

password `3gqisGdR0pjm6tpkDKdIWO2hSvchLeYH`

## Natas 2-3

In this level just check for the /robots.txt in the website
and we find s3cr3t directory is disallowed

![image](https://github.com/user-attachments/assets/5fa547f7-c80f-4c7f-95b9-1ec84d06a711)

password `QryZXc2e0zahULdHrtHxzyYkj59kUxLQ`

## Natas 3-4

you need to use a tool like burp suite or owasp zap to intercept the request and change the referer to natas5 

![image](https://github.com/user-attachments/assets/fc97d4d1-9fa6-4ee7-97a5-d6a6a3b7a54c)

![image](https://github.com/user-attachments/assets/c2929bde-17cd-446b-a18a-a2ae0fa2ba84)

password `0n35PkggAPm2zbEpOU802c0x0Msn1ToK`

## Natas 4-5

Just login on the webpage refresh the page a few times 

set the cookie: loggedin to 1

![image](https://github.com/user-attachments/assets/ba684f1e-8802-4ed5-8614-fcd181bc29d7)

send the request

![image](https://github.com/user-attachments/assets/b8510f82-4a99-474e-9685-1164e80a59bf)

password `0RoJwHdSKWFTYR5WuiAewauSuNaBXned`

## Natas 5-6

after looking at the sourc code there's this file includes/secret.inc

![image](https://github.com/user-attachments/assets/19276e3c-9213-4c8f-8ebd-1380a3303e34)

there is the secret in it's source code

![image](https://github.com/user-attachments/assets/3532a41e-65c4-4582-9828-f484cfed4d1e)

![image](https://github.com/user-attachments/assets/46c79cfa-cb70-4ae0-86c3-5ce51ec93039)

password `bmg8SvU1LizuWjx3y7xkNERkHxGre0GS`

## Natas 6-7
after looking at the hint at the page source

![image](https://github.com/user-attachments/assets/f2e64cb2-3cbd-44c9-a8e3-b5514bb3e036)

LFI is present without any sanitization

http://natas7.natas.labs.overthewire.org/index.php?page=about

so if we do `http://natas7.natas.labs.overthewire.org/index.php?page=/etc/natas_webpass/natas8`

![image](https://github.com/user-attachments/assets/64a5addf-0b37-41f8-8b9e-158e0c9a50a9)

password `xcoXLmzMkoIP9D7hlgPlh9XD7OgLAe5Q`

## Natas 7-8

after viewing [age source we find a encoded value

![image](https://github.com/user-attachments/assets/88a8edd1-0069-4daa-8aa5-045421883b1e)

as you can see in the function
first let's convert it from hex 
then reverse 
then from base64

![image](https://github.com/user-attachments/assets/6429d206-2a18-475d-b0e9-82f8f5ba817a)

![image](https://github.com/user-attachments/assets/987795b5-918d-4ab4-9754-94165a6fcf6f)

password `ZE1ck82lmdGIoErlhQgWND6j2Wzz6b6t`

## Natas 8-9

![image](https://github.com/user-attachments/assets/608801e2-e14b-4af5-9a10-9befa1b73682)

as you can see the variable is getting ececuted in a command 

let's try command injection

![image](https://github.com/user-attachments/assets/15849985-ec51-4721-99c1-35a593aaee65)

it is working

now

`whatever; cat /etc/natas_webpass/natas10`

![image](https://github.com/user-attachments/assets/38c9f6a2-8560-4397-8546-27a84f985955)

password `t7I5VHvpa14sJTUGV0cbEsbYfFP2dmOu`

## Natas 9-10

![image](https://github.com/user-attachments/assets/e334c5ea-02af-4011-8ea6-87c4ccb49132)

this is same as the previous one but there is basic filterung used 

let's check a online cheetsheet for command injection

and we found it

`%0Acat%20/etc/natas_webpass/natas11`

putting this in the needle variable

![image](https://github.com/user-attachments/assets/5c56022d-0559-44d7-9f36-283ab1147dbc)


password `UJdqkK1pTu6VLt9UHWAgRZz6sVUZ3lEk` 
