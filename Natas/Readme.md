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

