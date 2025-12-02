Game execution:

```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
```

Password: bandit0

# Bandit Level 0 -> Level 1

 **Level Goal**

The password for the next level is stored in a file called **readme** located in the home directory. Use this password to log into bandit1 using SSH. Whenever you find a password for a level, use SSH (on port 2220) to log into that level and continue the game.

 **Commands you may need to solve this level**

[ls](https://manpages.ubuntu.com/manpages/noble/man1/ls.1.html) , [cd](https://manpages.ubuntu.com/manpages/noble/man1/cd.1posix.html) , [cat](https://manpages.ubuntu.com/manpages/noble/man1/cat.1.html) , [file](https://manpages.ubuntu.com/manpages/noble/man1/file.1.html) , [du](https://manpages.ubuntu.com/manpages/noble/man1/du.1.html) , [find](https://manpages.ubuntu.com/manpages/noble/man1/find.1.html)

**TIP:** Create a file for notes and passwords on your local machine!

Passwords for levels are _not_ saved automatically. If you do not save them yourself, you will need to start over from bandit0.

Passwords also occasionally change. It is recommended to take notes on how to solve each challenge. As levels get more challenging, detailed notes are useful to return to where you left off, reference for later problems, or help others after you’ve completed the challenge.

```bash
cat readme

Congratulations on your first steps into the bandit game!!
Please make sure you have read the rules at https://overthewire.org/rules/
If you are following a course, workshop, walkthrough or other educational activity, please inform the instructor about the rules as well and encourage them to contribute to the OverTheWire community so we can keep these games free!
>
>The password you are looking for is: ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If

ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
```

# Bandit Level 1 → Level 2

The password for the next level is stored in a file called **-** located in the home directory

**Commands you may need to solve this level**

[ls](https://manpages.ubuntu.com/manpages/noble/man1/ls.1.html) , [cd](https://manpages.ubuntu.com/manpages/noble/man1/cd.1posix.html) , [cat](https://manpages.ubuntu.com/manpages/noble/man1/cat.1.html) , [file](https://manpages.ubuntu.com/manpages/noble/man1/file.1.html) , [du](https://manpages.ubuntu.com/manpages/noble/man1/du.1.html) , [find](https://manpages.ubuntu.com/manpages/noble/man1/find.1.html)


```bash
# Bandit Level 2 → Level 3

The password for the next level is stored in a file called `--spaces in this filename--` located in the home directory

## Commands you may need to solve this level

[ls](https://manpages.ubuntu.com/manpages/noble/man1/ls.1.html) , [cd](https://manpages.ubuntu.com/manpages/noble/man1/cd.1posix.html) , [cat](https://manpages.ubuntu.com/manpages/noble/man1/cat.1.html) , [file](https://manpages.ubuntu.com/manpages/noble/man1/file.1.html) , [du](https://manpages.ubuntu.com/manpages/noble/man1/du.1.html) , [find](https://manpages.ubuntu.com/manpages/noble/man1/find.1.html)
```


- Correcto Solución

```bash
cat ./-
```


>[!mensaje]
>263JGJPfgU6LtdEvgfWU1XP5yac29mFx

263JGJPfgU6LtdEvgfWU1XP5yac29mFx

Explanation: In Linux, when you use a command such as `cat -`, the hyphen `-` is not interpreted as a file name, but as a special parameter that means:

> “read from standard input (stdin)”.

This would cause the command to wait for you to type something, instead of opening the file. To do this, `./` is used, which takes any name or symbol as a real file.

# Bandit Level 2 → Level 3

The password for the next level is stored in a file called `--spaces in this filename--` located in the home directory

 **Commands you may need to solve this level**

[ls](https://manpages.ubuntu.com/manpages/noble/man1/ls.1.html) , [cd](https://manpages.ubuntu.com/manpages/noble/man1/cd.1posix.html) , [cat](https://manpages.ubuntu.com/manpages/noble/man1/cat.1.html) , [file](https://manpages.ubuntu.com/manpages/noble/man1/file.1.html) , [du](https://manpages.ubuntu.com/manpages/noble/man1/du.1.html) , [find](https://manpages.ubuntu.com/manpages/noble/man1/find.1.html)

```bash
bandit2@bandit:~$ ls

--spaces in this filename--

bandit2@bandit:~$ cat "./--spaces in this filename--"

MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx 
```

# Bandit Level 3 → Level 4

The password for the next level is stored in a hidden file in the **inhere** directory.

 Commands you may need to solve this level
 
[ls](https://manpages.ubuntu.com/manpages/noble/man1/ls.1.html) , [cd](https://manpages.ubuntu.com/manpages/noble/man1/cd.1posix.html) , [cat](https://manpages.ubuntu.com/manpages/noble/man1/cat.1.html) , [file](https://manpages.ubuntu.com/manpages/noble/man1/file.1.html) , [du](https://manpages.ubuntu.com/manpages/noble/man1/du.1.html) , [find](https://manpages.ubuntu.com/manpages/noble/man1/find.1.html)


```bash
bandit3@bandit:$ ls

inhere

bandit3@bandit$ cd inhere

bandit3@bandit:~/inhere

bandit3@bandit:~/inhere$ find


./...Hiding-From-You

bandit3@bandit:~/inhere$ cat "...Hiding-From-You"

2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ
```


# Bandit Level 4 → Level 5

Level Goal

The password for the next level is stored in the only human-readable file in the **inhere** directory. Tip: if your terminal is messed up, try the “reset” command.

 **Commands you may need to solve this level**

[ls](https://manpages.ubuntu.com/manpages/noble/man1/ls.1.html) , [cd](https://manpages.ubuntu.com/manpages/noble/man1/cd.1posix.html) , [cat](https://manpages.ubuntu.com/manpages/noble/man1/cat.1.html) , [file](https://manpages.ubuntu.com/manpages/noble/man1/file.1.html) , [du](https://manpages.ubuntu.com/manpages/noble/man1/du.1.html) , [find](https://manpages.ubuntu.com/manpages/noble/man1/find.1.html)


```bash
bandit4@bandit:$ ls

inhere

bandit4@bandit:~/inhere$ cd inhere

bandit4@bandit:~/inhere$ find

.

./-file02

./-file04

./-file08

./-file00

./-file07

./-file06

./-file01

./-file03

./-file05

./-file09

bandit4@bandit:~/inhere$ cat "."

cat: .: Is a directory

bandit4@bandit:~/inhere$ file "./-file02"

./-file02: OpenPGP Public Key

bandit4@bandit:~/inhere$ file "./-file04"

./-file04: data

bandit4@bandit:~/inhere$ file "./-file08"

./-file08: data

bandit4@bandit:~/inhere$ file "./-file00"

./-file00: data

bandit4@bandit:~/inhere$ file "./-file07"

./-file07: ASCII text

bandit4@bandit:~/inhere$ file "./-file06"

./-file06: data

bandit4@bandit:~/inhere$ file "./-file01"

./-file01: OpenPGP Public Key

bandit4@bandit:~/inhere$ file "./-file03"

./-file03: data

bandit4@bandit:~/inhere$ file "./-file05"

./-file05: data

bandit4@bandit:~/inhere$ file "./-file09"

./-file09: data

bandit4@bandit:~/inhere$ cat "./-file07"

4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw
```



# Bandit Level 5 → Level 6

The password for the next level is stored in a file somewhere under the **inhere** directory and has all of the following properties:

- human-readable
- 1033 bytes in size
- not executable

**Commands you may need to solve this level**

[ls](https://manpages.ubuntu.com/manpages/noble/man1/ls.1.html) , [cd](https://manpages.ubuntu.com/manpages/noble/man1/cd.1posix.html) , [cat](https://manpages.ubuntu.com/manpages/noble/man1/cat.1.html) , [file](https://manpages.ubuntu.com/manpages/noble/man1/file.1.html) , [du](https://manpages.ubuntu.com/manpages/noble/man1/du.1.html) , [find](https://manpages.ubuntu.com/manpages/noble/man1/find.1.html)

```bash
bandit5@bandit:~/inhere$ find
[180 files]

bandit5@bandit:~/inhere**$ find . -type f -size 1033c -exec file {} \;
./maybehere07/.file2: ASCII text, with very long lines (1000)

bandit5@bandit:~/inhere$ cat "./maybehere07/.file2"

HWasnPhtq9AVKe0dmk45nxy20cvUa6EG
```


#  Bandit Level 6 → Level 7

The password for the next level is stored **somewhere on the server** and has all of the following properties:

- owned by user bandit7
- owned by group bandit6
- 33 bytes in size

```bash
bandit6@bandit:~$ find
.
./.bash_logout
./.bashrc
./.profile

bandit6@bandit:~$ find / -type f -user bandit7 -group bandit6 -size 33c

# Many results, but a file named "/var/lib/dpkg/info/bandit7.password" has been found

bandit6@bandit:~$ cat "/var/lib/dpkg/info/bandit7.password"

morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj
```


# Bandit Level 7 → Level 8
The password for the next level is stored in the file **data.txt** next to the word **millionth**

 Commands you may need to solve this level

[man](https://manpages.ubuntu.com/manpages/noble/man1/man.1.html), grep, sort, uniq, strings, base64, tr, tar, gzip, bzip2, xxd

```bash
bandit7@bandit:~$ ls

data.txt

bandit7@bandit:~$ grep millionth data.txt

bandit7@bandit:~$ dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc
```


# Bandit Level 8 → Level 9

The password for the next level is stored in the file **data.txt** and is the only line of text that occurs only once

 **Commands you may need to solve this level**

grep, sort, uniq, strings, base64, tr, tar, gzip, bzip2, xxd

```bash
bandit8@bandit:~$ ls

data.txt

bandit8@bandit:~$ sort data.txt | uniq -u

4CKMh1JI91bUIZZPXDqGanal4xvAg0JM
```

# Bandit Level 9 → Level 10

The password for the next level is stored in the file **data.txt** in one of the few human-readable strings, preceded by several ‘=’ characters.

**Commands you may need to solve this level**

grep, sort, uniq, strings, base64, tr, tar, gzip, bzip2, xxd

```bash
bandit9@bandit:~$ ls

data.txt

bandit9@bandit:~$ strings data.txt | grep -n "="

11:**==========** the

49:9**=**H`

60:[!#**=**Z

72:**==========** password

83:xWf**=**

91:f\Z'**==========** is

100:e**=**i{\#

138:/1**=**s

163:nS**=**F

196:M**=**Sl

197:**=**LGT

217:y **=**1

220:**==========** FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey

241:'+Y**=**+
```


# Bandit Level 10 → Level 11

The password for the next level is stored in the file **data.txt**, which contains base64 encoded data

Commands you may need to solve this level

grep, sort, uniq, strings, base64, tr, tar, gzip, bzip2, xxd

```bash
bandit10@bandit:~$ ls

data.txt

bandit10@bandit:~$ base64 base64 --decode data.txt

The password is dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr
```


# Bandit Level 11 → Level 12
The password for the next level is stored in the file **data.txt**, where all lowercase (a-z) and uppercase (A-Z) letters have been rotated by 13 positions

 **Commands you may need to solve this level**

grep, sort, uniq, strings, base64, tr, tar, gzip, bzip2, xxd

```bash
bandit11@bandit:~$ ls

data.txt

bandit11@bandit:~$ cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'

The password is 7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4

bandit11@bandit:~$
```


# Bandit Level 12 → Level 13
The password for the next level is stored in the file **data.txt**, which is a hexdump of a file that has been repeatedly compressed. For this level it may be useful to create a directory under /tmp in which you can work. Use mkdir with a hard to guess directory name. Or better, use the command “mktemp -d”. Then copy the datafile using cp, and rename it using mv (read the manpages!)

**Commands you may need to solve this level**

grep, sort, uniq, strings, base64, tr, tar, gzip, bzip2, xxd, mkdir, cp, mv, file


```bash
bandit12@bandit:~$ cd /tmp/tmp.w31t4ijqcs

bandit12@bandit:/tmp/tmp.w31t4ijqcs$ ls

data.txt

bandit12@bandit:/tmp/tmp.w31t4ijqcs$ file data.txt

data.txt: ASCII text

bandit12@bandit:/tmp/tmp.w31t4ijqcs$ cat data.txt

bandit12@bandit:/tmp/tmp.w31t4ijqcs$ xxd -r data.txt data.bin

bandit12@bandit:/tmp/tmp.w31t4ijqcs$ file data.bin

data.bin: gzip compressed data, was "data2.bin", last modified: Tue Oct 14 09:26:06 2025, max compression, from Unix, original size modulo 2^32 564

bandit12@bandit:/tmp/tmp.w31t4ijqcs$ mv data.bin data.gz

bandit12@bandit:/tmp/tmp.w31t4ijqcs$ ls

data.gz  data.txt

bandit12@bandit:/tmp/tmp.w31t4ijqcs$ gzip -d data.gz

bandit12@bandit:/tmp/tmp.w31t4ijqcs$ ls

data  data.txt

bandit12@bandit:/tmp/tmp.w31t4ijqcs$ file data

data: bzip2 compressed data, block size = 900k

bandit12@bandit:/tmp/tmp.w31t4ijqcs$ bzip2 -d data

bzip2: Cant guess original name for data -- using data.out

bandit12@bandit:/tmp/tmp.w31t4ijqcs$ ls

data.out  data.txt

bandit12@bandit:/tmp/tmp.w31t4ijqcs$ file data.out

data.out: gzip compressed data, was "data4.bin", last modified: Tue Oct 14 09:26:06 2025, max compression, from Unix, original size modulo 2^32 20480

bandit12@bandit:/tmp/tmp.w31t4ijqcs$ mv data.out data.gz

bandit12@bandit:/tmp/tmp.w31t4ijqcs$ ls

data.gz  data.txt

bandit12@bandit:/tmp/tmp.w31t4ijqcs$ gzip -d data.gz

bandit12@bandit:/tmp/tmp.w31t4ijqcs$ ls

data  data.txt

bandit12@bandit:/tmp/tmp.w31t4ijqcs$ file data

data: POSIX tar archive (GNU)

bandit12@bandit:/tmp/tmp.w31t4ijqcs$ man tar

bandit12@bandit:/tmp/tmp.w31t4ijqcs$ tar -xf data

bandit12@bandit:/tmp/tmp.w31t4ijqcs$ ls

data  data5.bin  data.txt

bandit12@bandit:/tmp/tmp.w31t4ijqcs$ file data5.bin

data5.bin: POSIX tar archive (GNU)

bandit12@bandit:/tmp/tmp.w31t4ijqcs$ tar -xf data5.bin

bandit12@bandit:/tmp/tmp.w31t4ijqcs$ ls

data  data5.bin  data6.bin  data.txt

bandit12@bandit:/tmp/tmp.w31t4ijqcs$ tar -xf data6.bin

bandit12@bandit:/tmp/tmp.w31t4ijqcs$ ls

data  data5.bin  data6.bin  data8.bin  data.txt

bandit12@bandit:/tmp/tmp.w31t4ijqcs$ file data8.bin

data8.bin: gzip compressed data, was "data9.bin", last modified: Tue Oct 14 09:26:06 2025, max compression, from Unix, original size modulo 2^32 49

bandit12@bandit:/tmp/tmp.w31t4ijqcs$ mv data8.bin data8.gz

bandit12@bandit:/tmp/tmp.w31t4ijqcs$ ls

data  data5.bin  data6.bin  data8.gz  data.txt

bandit12@bandit:/tmp/tmp.w31t4ijqcs$ gzip -d data8.gz

bandit12@bandit:/tmp/tmp.w31t4ijqcs$ ls

data  data5.bin  data6.bin  data8  data.txt

bandit12@bandit:/tmp/tmp.w31t4ijqcs$ file data8

data8: ASCII text

bandit12@bandit:/tmp/tmp.w31t4ijqcs$ cat data8

The password is FO5dwFsc0cbaIiH0h8J2eUks2vdTDwAn

```



# Bandit Level 13 → Level 14

The password for the next level is stored in **/etc/bandit_pass/bandit14 and can only be read by user bandit14**. For this level, you don’t get the next password, but you get a private SSH key that can be used to log into the next level. Look at the commands that logged you into previous bandit levels, and find out how to use the key for this level.

**Commands you may need to solve this level**

ssh, scp, umask, chmod, cat, nc, install

```bash
cristina_cgv@MacBook-Air-de-Cristina ~ % scp -P 2220 bandit13@bandit.labs.overthewire.org:~/sshkey.private .

bandit13@bandit.labs.overthewire.orgs password: 

sshkey.private                                100% 1679    13.9KB/s   00:00    

cristina_cgv@MacBook-Air-de-Cristina ~ % chmod 600 sshkey.private

cristina_cgv@MacBook-Air-de-Cristina ~ % ssh -i sshkey.private bandit14@bandit.labs.overthewire.org -p 2220

bandit14@bandit:~$ find
.
./.bash_logout
./.bashrc
./.profile
./.ssh
./.ssh/authorized_keys

bandit14@bandit:~$ find /etc/bandit_pass/bandit14
/etc/bandit_pass/bandit14

bandit14@bandit:~$ cat /etc/bandit_pass/bandit14

MU4VWeTyJk8ROof1qqmcBPaLh7lDCPvS
```


# Bandit Level 14 → Level 15
The password for the next level can be retrieved by submitting the password of the current level to **port 30000 on localhost**.


**Commands you may need to solve this level**

ssh, telnet, nc, openssl, s_client, nmap

ssh bandit14@bandit.labs.overthewire.org -p 2220

```bash
bandit14@bandit:~$ telnet localhost 30000

Trying 127.0.0.1...

Connected to localhost.

Escape character is '^]'.

MU4VWeTyJk8ROof1qqmcBPaLh7lDCPvS

Correct!

8xCjnmgoKbGLhHFAZlGE5Tmu4M2tKJQo

Connection closed by foreign host.
```


# Bandit Level 15 → Level 16

The password for the next level can be retrieved by submitting the password of the current level to **port 30001 on localhost** using SSL/TLS encryption.

**Helpful note: Getting “DONE”, “RENEGOTIATING” or “KEYUPDATE”? Read the “CONNECTED COMMANDS” section in the manpage.**

ssh bandit16@bandit.labs.overthewire.org -p 2220


```bash
**bandit15@bandit**:**~**$ openssl s_client -connect localhost:30001

8xCjnmgoKbGLhHFAZlGE5Tmu4M2tKJQo

Correct!

kSkvUpMQ7lBYyCM4GBPvCvT1BfWRy0Dx
```


# Bandit Level 16 → Level 17

The credentials for the next level can be retrieved by submitting the password of the current level to **a port on localhost in the range 31000 to 32000**. First find out which of these ports have a server listening on them. Then find out which of those speak SSL/TLS and which don’t. There is only 1 server that will give the next credentials, the others will simply send back to you whatever you send to it.

**Helpful note: Getting “DONE”, “RENEGOTIATING” or “KEYUPDATE”? Read the “CONNECTED COMMANDS” section in the manpage.**

Commands you may need to solve this level

ssh, telnet, nc, ncat, socat, openssl, s_client, nmap, netstat, ss

```bash
bandit16@bandit:~$ nmap -p 31000-32000 localhost
Starting Nmap 7.94SVN ( https://nmap.org ) at 2025-11-20 17:26 UTC

Nmap scan report for localhost (127.0.0.1)

Host is up (0.00018s latency).

Not shown: 996 closed tcp ports (conn-refused)

PORT      STATE SERVICE

31046/tcp open  unknown
31518/tcp open  unknown
31691/tcp open  unknown
31790/tcp open  unknown
31960/tcp open  unknown

bandit16@bandit:~$ echo "kSkvUpMQ7lBYyCM4GBPvCvT1BfWRy0Dx" | openssl s_client -connect localhost:31790 -ign_eof

---
```

```bash
echo "-----BEGIN RSA PRIVATE KEY-----
MIIEogIBAAKCAQEAvmOkuifmMg6HL2YPIOjon6iWfbp7c3jx34YkYWqUH57SUdyJ
imZzeyGC0gtZPGujUSxiJSWI/oTqexh+cAMTSMlOJf7+BrJObArnxd9Y7YT2bRPQ
Ja6Lzb558YW3FZl87ORiO+rW4LCDCNd2lUvLE/GL2GWyuKN0K5iCd5TbtJzEkQTu
DSt2mcNn4rhAL+JFr56o4T6z8WWAW18BR6yGrMq7Q/kALHYW3OekePQAzL0VUYbW
JGTi65CxbCnzc/w4+mqQyvmzpWtMAzJTzAzQxNbkR2MBGySxDLrjg0LWN6sK7wNX
x0YVztz/zbIkPjfkU1jHS+9EbVNj+D1XFOJuaQIDAQABAoIBABagpxpM1aoLWfvD
KHcj10nqcoBc4oE11aFYQwik7xfW+24pRNuDE6SFthOar69jp5RlLwD1NhPx3iBl
J9nOM8OJ0VToum43UOS8YxF8WwhXriYGnc1sskbwpXOUDc9uX4+UESzH22P29ovd
d8WErY0gPxun8pbJLmxkAtWNhpMvfe0050vk9TL5wqbu9AlbssgTcCXkMQnPw9nC
YNN6DDP2lbcBrvgT9YCNL6C+ZKufD52yOQ9qOkwFTEQpjtF4uNtJom+asvlpmS8A
vLY9r60wYSvmZhNqBUrj7lyCtXMIu1kkd4w7F77k+DjHoAXyxcUp1DGL51sOmama
+TOWWgECgYEA8JtPxP0GRJ+IQkX262jM3dEIkza8ky5moIwUqYdsx0NxHgRRhORT
8c8hAuRBb2G82so8vUHk/fur85OEfc9TncnCY2crpoqsghifKLxrLgtT+qDpfZnx
SatLdt8GfQ85yA7hnWWJ2MxF3NaeSDm75Lsm+tBbAiyc9P2jGRNtMSkCgYEAypHd
HCctNi/FwjulhttFx/rHYKhLidZDFYeiE/v45bN4yFm8x7R/b0iE7KaszX+Exdvt
SghaTdcG0Knyw1bpJVyusavPzpaJMjdJ6tcFhVAbAjm7enCIvGCSx+X3l5SiWg0A
R57hJglezIiVjv3aGwHwvlZvtszK6zV6oXFAu0ECgYAbjo46T4hyP5tJi93V5HDi
Ttiek7xRVxUl+iU7rWkGAXFpMLFteQEsRr7PJ/lemmEY5eTDAFMLy9FL2m9oQWCg
R8VdwSk8r9FGLS+9aKcV5PI/WEKlwgXinB3OhYimtiG2Cg5JCqIZFHxD6MjEGOiu
L8ktHMPvodBwNsSBULpG0QKBgBAplTfC1HOnWiMGOU3KPwYWt0O6CdTkmJOmL8Ni
blh9elyZ9FsGxsgtRBXRsqXuz7wtsQAgLHxbdLq/ZJQ7YfzOKU4ZxEnabvXnvWkU
YOdjHdSOoKvDQNWu6ucyLRAWFuISeXw9a/9p7ftpxm0TSgyvmfLF2MIAEwyzRqaM
77pBAoGAMmjmIJdjp+Ez8duyn3ieo36yrttF5NSsJLAbxFpdlc1gvtGCWW+9Cq0b
-----END RSA PRIVATE KEY-----" >
```

- ! Next, the key step lies in the commando scp, which is used to securely copy files between machines using SSH. In this specific case, the goal is to copy the private key to both the bandit 16 server and the local computer. To achieve that, it is necessary to complete the following steps.


```bash
# 1.Create a new folder to save the private key in the server 16 itself:
bandit16@bandit:~$ mkdir /tmp/cgvtmp

# 2. Create a new file with nano bandit17key and name it as "/tmp/bandit17key"
# Now you have to get permissions in the folder where the file is:

chmod 600 /tmp/cgvtmp/bandit17key

# 3. You have to copy the private key from the Bandit Server to your computer:
   scp -P 2220 bandit16@bandit.labs.overthewire.org:/tmp/cgvtmp/bandit17key "local folder address where you want to save the private key"

# 4. Adjust permissions to the local folder where the private key is
chmod 600 "[local folder's name where the private key is]"

5. Use the private key tu enter in bandite 17 Server
   
   ssh -i "folder name" bandit17@bandit.labs.overthewire.org -p 2220
```

ssh -i "/Users/cristina_cgv/Desktop/Over The Wire/bandit17key" bandit17@bandit.labs.overthewire.org -p 2220

- ! Reference: https://blog.othmanemoutaouakkil.com/write-ups/hacking-challenges/otw/bandit/level-16-17



# Bandit Level 17 → Level 18

There are 2 files in the homedirectory: **passwords.old and passwords.new**. The password for the next level is in **passwords.new** and is the only line that has been changed between **passwords.old and passwords.new**

**NOTE: if you have solved this level and see ‘Byebye!’ when trying to log into bandit18, this is related to the next level, bandit19**

**Commands you may need to solve this level**

cat, grep, ls, diff


```bash
bandit17@bandit:~$ ls
passwords.new  passwords.old

bandit17@bandit:~$ diff passwords.new passwords.old
42c42 # This is the line where is the difference between the two files
< x2gLTTjFwMOhQ8oWNbMN362QKxfRqGlO #This is the password
---
> pGozC8kOHLkBMOaL0ICPvLV1IjQ5F1VA 
```



# Bandit Level 18 → Level 19
The password for the next level is stored in a file **readme** in the homedirectory. Unfortunately, someone has modified **.bashrc** to log you out when you log in with SSH.

**Commands you may need to solve this level**

ssh, ls, cat

```bash
ssh bandit18@bandit.labs.overthewire.org -p 2220 cat readme

bandit18@bandit.labs.overthewire.orgs password: 
cGWpMaKXVwDUNgPAVJbWYuGHVn9zl3j8 # This is the password for the next level
```

 ssh bandit19@bandit.labs.overthewire.org -p 2220


# Bandit Level 19 → Level 20

To gain access to the next level, you should use the setuid binary in the homedirectory. Execute it without arguments to find out how to use it. The password for this level can be found in the usual place (/etc/bandit_pass), after you have used the setuid binary.

```bash
# The key is to read the file /etc/bandit_pass/bandit20 using bandit20' permissions

bandit19@bandit:~$ ls
bandit20-do
bandit19@bandit:~$ ./bandit20-do cat /etc/bandit_pass/bandit20
0qXahG8ZjOVMN9Ghs7iOWsCfZyXOUbYO # This is the password for the next level
```


# Bandit Level 20 → Level 21

There is a setuid binary in the homedirectory that does the following: it makes a connection to localhost on the port you specify as a commandline argument. It then reads a line of text from the connection and compares it to the password in the previous level (bandit20). If the password is correct, it will transmit the password for the next level (bandit21).

**NOTE:** Try connecting to your own network daemon to see if it works as you think

Commands you may need to solve this level

ssh, nc, cat, bash, screen, tmux, Unix ‘job control’ (bg, fg, jobs, &, CTRL-Z, …)

 ssh bandit20@bandit.labs.overthewire.org -p 2220
 
- ! To discover the password for the next level, both Terminal 1 and Terminal 2 are needed. To display both, you need to write 'tmux' on the terminal and create two screens (terminal 1 and terminal 2). To do so, you have to write first `ctrl b` (vertical display) and then `shift %`. To change screen, you have to write `ctrol b` and then `<-` or `->`

```bash

# Terminal 1 (Server with nc)

## Step 1
bandit20@bandit:~$ ls     
suconnect
bandit20@bandit:~$ nc -l 3000 # Listen to the port 3000

## Step 2
0qXahG8ZjOVMN9Ghs7iOWsCfZyXOUbYO # Write the password of the previous level and ENTER
EeoULMCra2q0dSkYj561DX7s1CpBuOBt # If the password for the next level will appear in this same terminal.
```


```bash
# Terminal 2

# Step 1
bandit20@bandit:~$ ./suconnect 3000 # suconnect connect to the port 3000 and waits to recieve the password from Terminal 1

# 
Read: 0qXahG8ZjOVMN9Ghs7iOWsCfZyXOUbYO # The binnary reads the password sended by nc and verifies it. If it is correct, sends the passsword back to terminal 1
Password matches, sending next password
```



![[Level 20.png]]



# Bandit Level 21 → Level 22
A program is running automatically at regular intervals from **cron**, the time-based job scheduler. Look in **/etc/cron.d/** for the configuration and see what command is being executed.

**Commands you may need to solve this level**

cron, crontab, crontab(5) (use “man 5 crontab” to access this)


```bash
bandit21@bandit:~$ ls /etc/cron.d
behemoth4_cleanup  cronjob_bandit22  cronjob_bandit24  leviathan5_cleanup    otw-tmp-dir
clean_tmp          cronjob_bandit23  e2scrub_all       manpage3_resetpw_job  sysstat
bandit21@bandit:~$ cat /usr/bin/cronjob_bandit22.sh
#!/bin/bash
chmod 644 /tmp/t7O6lds9S0RqQh9aMcz6ShpAoZKF7fgv
cat /etc/bandit_pass/bandit22 > /tmp/t7O6lds9S0RqQh9aMcz6ShpAoZKF7fgv

bandit21@bandit:~$ file /tmp/t7O6lds9S0RqQh9aMcz6ShpAoZKF7fgv
/tmp/t7O6lds9S0RqQh9aMcz6ShpAoZKF7fgv: ASCII text
bandit21@bandit:~$ cat /tmp/t7O6lds9S0RqQh9aMcz6ShpAoZKF7fgv
tRae0UfB9v0UzbCdn9cY0gQnds9GF58Q # Password for the next level
```


- ! Important: 
  - **bin:** Carpeta estándar para ejecutables y scripts.
  - **.sh:** Script de shell.


# Bandit Level 22 → Level 23
A program is running automatically at regular intervals from **cron**, the time-based job scheduler. Look in **/etc/cron.d/** for the configuration and see what command is being executed.

**NOTE:** Looking at shell scripts written by other people is a very useful skill. The script for this level is intentionally made easy to read. If you are having problems understanding what it does, try executing it to see the debug information it prints.

**Commands you may need to solve this level**

cron, crontab, crontab(5) (use “man 5 crontab” to access this)

```bash
bandit22@bandit:~$ ls /etc/cron.d/
behemoth4_cleanup  cronjob_bandit22  cronjob_bandit24  leviathan5_cleanup    otw-tmp-dir
clean_tmp          cronjob_bandit23  e2scrub_all       manpage3_resetpw_job  sysstat
bandit22@bandit:~$ cat /usr/bin/cronjob_bandit23.sh
#!/bin/bash

myname=$(whoami)
mytarget=$(echo I am user $myname | md5sum | cut -d ' ' -f 1)

echo "Copying passwordfile /etc/bandit_pass/$myname to /tmp/$mytarget"

cat /etc/bandit_pass/$myname > /tmp/$mytarget
bandit22@bandit:~$ echo I am user bandit23 | md5sum | cut -d ' ' -f 1
8ca319486bfbbc3663ea0fbe81326349
bandit22@bandit:~$ cat /tmp/8ca319486bfbbc3663ea0fbe81326349
0Zf11ioIjMVN551jX3CmStKLYqjk54Ga
```

# Bandit Level 23 → Level 24

A program is running automatically at regular intervals from **cron**, the time-based job scheduler. Look in **/etc/cron.d/** for the configuration and see what command is being executed.

**NOTE:** This level requires you to create your own first shell-script. This is a very big step and you should be proud of yourself when you beat this level!

**NOTE 2:** Keep in mind that your shell script is removed once executed, so you may want to keep a copy around…

**Commands you may need to solve this level**

chmod, cron, crontab, crontab(5) (use “man 5 crontab” to access this)

```bash
bandit23@bandit:~$ cat /usr/bin/cronjob_bandit24.sh
#!/bin/bash

myname=$(whoami)

cd /var/spool/$myname/foo
echo "Executing and deleting all scripts in /var/spool/$myname/foo:"
for i in * .*;
do
    if [ "$i" != "." -a "$i" != ".." ];
    then
        echo "Handling $i"
        owner="$(stat --format "%U" ./$i)"
        if [ "${owner}" = "bandit23" ]; then
            timeout -s 9 60 ./$i
        fi
        rm -f ./$i
    fi
done
bandit23@bandit:~$ ls /etc/
bandit23@bandit:~$ echo "cat /etc/bandit_pass/bandit24 > /tmp/password.txt" > /tmp/24.sh
bandit23@bandit:~$ chmod +x /tmp/24.sh
bandit23@bandit:~$ cp /tmp/24.sh /var/spool/bandit24/foo/
bandit23@bandit:~$ cat /tmp/password.txt
gb8KRRCsshuZXI0tUuR6ypOFjiZbf3G8
```


# Bandit Level 24 → Level 25

A daemon is listening on port 30002 and will give you the password for bandit25 if given the password for bandit24 and a secret numeric 4-digit pincode. There is no way to retrieve the pincode except by going through all of the 10000 combinations, called brute-forcing.  
You do not need to create new connections each time.


- ! To complete this exercise, two steps are required: 1. Create a .sh script on server24  so that it can execute it. To do so, it's important to use the folder /tmp, which not requieres permissions and create the file with the commando `nano`. 2. Connect to server24 with the current password and run the script.


3. Create the script

```bash
#!/bin/bash
password="gb8KRRCsshuZXI0tUuR6ypOFjiZbf3G8"

for pin in $(seq -w 0000 9999); do
  echo "$password $pin"
done | nc localhost 30002
```


```bash
bandit24@bandit:~$ find /tmp/mibrutefolder 
/tmp/mibrutefolder
bandit24@bandit:~$ nano /tmp/mibrutefolder/bruteforce.sh 
bandit24@bandit:~$ ls /tmp/mibrutefolder
bruteforce.sh


chmod +x /tmp/mibrutefolder/bruteforce.sh

/tmp/mibrutefolder/bruteforce.sh

Correct!
The password of user bandit25 is iCi86ttT4KSNe1armKiwbQNmB3YJP3q4
```


# Bandit Level 25 → Level 26

Level Goal

Logging into bandit26 from bandit25 should be fairly easy… The shell for user bandit26 is not **/bin/bash**, but something else. Find out what it is, how it works and how to break out of it.

> NOTE: if you’re a Windows user and typically use Powershell to `ssh` into bandit: Powershell is known to cause issues with the intended solution to this level. You should use command prompt instead.

- ! This exercise only work using Linux and Windows. If you have a macOS, you would need install a VM.

```bash
bandit25@bandit:~$ cat /etc/passwd | grep bandit26
bandit26:x:11026:11026:bandit level 26:/home/bandit26:/usr/bin/showtext
bandit25@bandit:~$ cat /usr/bin/showtext
#!/bin/sh

export TERM=linux

exec more ~/text.txt
exit 0

ssh -i bandit26.sshkey bandit26@bandit.labs.overthewire.org -p 2220
```


https://alexdomnit.com/post/bandit27/

# Bandit Level 27 → Level 28

There is a git repository at `ssh://bandit27-git@bandit.labs.overthewire.org/home/bandit27-git/repo` via the port `2220`. The password for the user `bandit27-git` is the same as for the user `bandit27`.

Clone the repository and find the password for the next level.

- ! You can't create the bandit27 repository in the bandit27 server itself because you don't haver permissions to do it so. Therefore, you'll need to create a copy of bandit27 server in your local machine and clone it from there.

```bash
cgv06@Macbook-Air ~ %  mkdir ~/bandit27_repository
cgv06@Macbook-Air ~ % cd ~/bandit27_repository
git clone ssh://bandit27-git@bandit.labs.overthewire.org:2220/home/bandit27-git/repo
bandit27-git@bandit.labs.overthewire.orgs password: 
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.
cgv06@Macbook-Air bandit27_repository % ls
repo
cgv06@Macbook-Air  bandit27_repository % file repo
repo: directory
cgv06@Macbook-Air  bandit27_repository % cd repo
cgv06@Macbook-Air repo % ls
README
cat README
The password to the next level is: Yz9IpL0sBcCeuG7m9uQFt8ZNpS4HZRcN
```



# Bandit Level 27 → Level 28
There is a git repository at `ssh://bandit28-git@bandit.labs.overthewire.org/home/bandit28-git/repo` via the port `2220`. The password for the user `bandit28-git` is the same as for the user `bandit28`.

Clone the repository and find the password for the next level.

**Commands you may need to solve this level**

git

```bash
cgv06@Macbook-Air ~ %  mkdir ~/bandit28_repository
cgv06@Macbook-Air ~ % cd ~/bandit28_repository
git clone ssh://bandit27-git@bandit.labs.overthewire.org:2220/home/bandit27-git/repo
bandit27-git@bandit.labs.overthewire.orgs password: 
remote: Enumerating objects: 9, done.
remote: Counting objects: 100% (9/9), done.
remote: Compressing objects: 100% (6/6), done.
remote: Total 9 (delta 2), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (9/9), done.
Resolving deltas: 100% (2/2), done.
cgv06@Macbook-Air bandit28_repository % ls
repo
cgv06@Macbook-Air bandit28_repository % cd repo
cgv06@Macbook-Air repo % ls
README.md
cgv06@Macbook-Air % cat README.md
# Bandit Notes
Some notes for level29 of bandit.

## credentials

- username: bandit29
- password: xxxxxxxxxx

cgv06@Macbook-Air repo % git 
# It is shown all the logs 
cgv06@Macbook-Air repo % git show HEAD
commit b5ed4b5a3499533c2611217c8780e8ead48609f6 (HEAD -> master, origin/master, origin/HEAD)
Author: Morla Porla <morla@overthewire.org>
Date:   Tue Oct 14 09:26:24 2025 +0000

    fix info leak

diff --git a/README.md b/README.md
index d4e3b74..5c6457b 100644
--- a/README.md
+++ b/README.md
@@ -4,5 +4,5 @@ Some notes for level29 of bandit.
 ## credentials
 
 - username: bandit29
-- password: 4pT1t5DENaYuqnqvadYs1oE4QLCdjmJ7
+- password: xxxxxxxxxx
```


# Bandit Level 29 → Level 30

There is a git repository at `ssh://bandit29-git@bandit.labs.overthewire.org/home/bandit29-git/repo` via the port `2220`. The password for the user `bandit29-git` is the same as for the user `bandit29`.

Clone the repository and find the password for the next level.

**Commands you may need to solve this level**

git

- !  At this level, the information will not only be in previous commits. You need to explore other branches of the repository.


```bash
cgv06@Macbook-Air ~ % mkdir ~/bandit29_repository

cgv06@Macbook-Air ~ % cd bandit29_repository
cgv06@Macbook-Air  bandit29_repository % git clone ssh://bandit29-git@bandit.labs.overthewire.org:2220/home/bandit29-git/repo bandit29_repo
Cloning into 'bandit29_repo'...
bandit29-git@bandit.labs.overthewire.orgs password: 
remote: Enumerating objects: 16, done.
remote: Counting objects: 100% (16/16), done.
remote: Compressing objects: 100% (11/11), done.
remote: Total 16 (delta 2), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (16/16), 1.44 KiB | 92.00 KiB/s, done.
Resolving deltas: 100% (2/2), done.
cgv06@Macbook-Air  bandit29_repository % ls
bandit29_repo
cgv06@Macbook-Air  bandit29_repository % cd bandit29_repo
cgv06@Macbook-Air  bandit29_repo % ls
README.md
cgv06@Macbook-Air  bandit29_repo % cat README.md
# Bandit Notes
Some notes for bandit30 of bandit.

## credentials

- username: bandit30
- password: <no passwords in production!>
  
cgv06@Macbook-Air  bandit29_repo % git branch -a       
* master
  remotes/origin/HEAD -> origin/master
  remotes/origin/dev
  remotes/origin/master
  remotes/origin/sploits-dev
cgv06@Macbook-Air  bandit29_repo % git checkout dev
Switched to branch 'dev'
Your branch is up to date with 'origin/dev'.
cgv06@Macbook-Air  bandit29_repo % ls
README.md       code
cgv06@Macbook-Air  bandit29_repo % cat README.md
# Bandit Notes
Some notes for bandit30 of bandit.

## credentials

- username: bandit30
- password: qp30ex3VLz5MDG1n91YowTv4Q8l7CDZL
```


# Bandit Level 30 → Level 31

There is a git repository at `ssh://bandit30-git@bandit.labs.overthewire.org/home/bandit30-git/repo` via the port `2220`. The password for the user `bandit30-git` is the same as for the user `bandit30`.

Clone the repository and find the password for the next level.

**Commands you may need to solve this level**

git

- ! This time it's not just about commits or branches. Git has more places where it can hide information.

```bash
cgv06@Macbook-Air ~ % mkdir bandit30_repository  
cgv06@Macbook-Air ~ % cd bandit30_repository 
cgv06@Macbook-Air bandit30_repository % git clone ssh://bandit30-git@bandit.labs.overthewire.org:2220/home/bandit30-git/repo bandit30_repo
Cloning into 'bandit30_repo'...
bandit30-git@bandit.labs.overthewire.orgs password: 
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (4/4), done.
cgv06@Macbook-Air bandit30_repository % ls
bandit30_repo
cgv06@Macbook-Air bandit30_repository % cd bandit30_repo
cgv06@Macbook-Air bandit30_repo % ls
README.md
cgv06@Macbook-Air bandit30_repo % cat README.md
just an epmty file... muahaha
cgv06@Macbook-Air bandit30_repo % git tag  
secret
cgv06@Macbook-Air bandit30_repo % git show secret
fb5S2xb7bRyFmAvQYQGEqsbhVyJqhnDy
```

# Bandit Level 31 → Level 32

There is a git repository at `ssh://bandit31-git@bandit.labs.overthewire.org/home/bandit31-git/repo` via the port `2220`. The password for the user `bandit31-git` is the same as for the user `bandit31`.

Clone the repository and find the password for the next level.

**Commands you may need to solve this level**

git

- ! 
**Necesitas crear:**

- **Archivo**: `key.txt`
- **Contenido**: `'May I come in?'`
- **Acción**: Hacer **push** a la rama **master**


```bash
cgv06@Macbook-Air ~ % mkdir bandit31_repository 
cgv06@Macbook-Air ~ % cd bandit31_repository 
cgv06@Macbook-Air bandit31_repository % git clone ssh://bandit31-git@bandit.labs.overthewire.org:2220/home/bandit31-git/repo bandit31_repo
Cloning into 'bandit31_repo'...

bandit31-git@bandit.labs.overthewire.orgs password: 
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (4/4), done.
cgv06@Macbook-Air bandit31_repository % ls 
bandit31_repo
cgv06@Macbook-Air bandit31_repository % cd bandit31_repo
cgv06@Macbook-Air bandit31_repo % ls
README.md
cgv06@Macbook-Air bandit31_repo % cat README.md
This time your task is to push a file to the remote repository.

Details:
    File name: key.txt
    Content: 'May I come in?'
    Branch: master

cgv06@Macbook-Air bandit31_repo % ls   
README.md
cgv06@Macbook-Air bandit31_repo % ls -la
total 16
drwxr-xr-x   5 [user name]  staff  160 Nov 27 09:12 .
drwxr-xr-x   3 [user name]   staff   96 Nov 27 09:12 ..
drwxr-xr-x  12 [user name]   staff  384 Nov 27 09:12 .git
-rw-r--r--   1 [user name]   staff    6 Nov 27 09:12 .gitignore
-rw-r--r--   1 [user name]   staff  147 Nov 27 09:12 README.md
cgv06@Macbook-Air bandit31_repo % cat .gitignore
*.txt
cgv06@Macbook-Air bandit31_repo % echo "May I come in?" > key.txt
cgv06@Macbook-Air bandit31_repo % git add key.txt

The following paths are ignored by one of your .gitignore files:
key.txt
hint: Use -f if you really want to add them.
hint: Turn this message off by running
hint: "git config advice.addIgnoredFile false"
cgv06@Macbook-Airbandit31_repo % git add -f key.txt
cgv06@Macbook-Air bandit31_repo % git commit -m "Add required key.txt file"
[master ebe5eb9] Add required key.txt file
 1 file changed, 1 insertion(+)
 create mode 100644 key.txt
cgv06@Macbook-Air bandit31_repo % git push origin master

backend: gibson-1
bandit31-git@bandit.labs.overthewire.orgs password: 
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 341 bytes | 341.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote: ### Attempting to validate files... ####
remote: 
remote: .oOo.oOo.oOo.oOo.oOo.oOo.oOo.oOo.oOo.oOo.
remote: 
remote: Well done! Here is the password for the next level:
remote: 3O9RfhqyAlVBEZpVb6LYStshZoqoSx5K 
remote: 
remote: .oOo.oOo.oOo.oOo.oOo.oOo.oOo.oOo.oOo.oOo.
remote: 
To ssh://bandit.labs.overthewire.org:2220/home/bandit31-git/repo
 ! [remote rejected] master -> master (pre-receive hook declined)
error: failed to push some refs to 'ssh://bandit.labs.overthewire.org:2220/home/bandit31-git/repo'
```



# Bandit Level 32 → Level 33

After all this `git` stuff, it’s time for another escape. Good luck!

 **Commands you may need to solve this level**

sh, man

```bash
$0
$ find /etc/bandit_pass
/etc/bandit_pass
/etc/bandit_pass/bandit15
/etc/bandit_pass/bandit23
/etc/bandit_pass/bandit30
/etc/bandit_pass/bandit29
/etc/bandit_pass/bandit0
/etc/bandit_pass/bandit8
/etc/bandit_pass/bandit21
/etc/bandit_pass/bandit20
/etc/bandit_pass/bandit13
/etc/bandit_pass/bandit32
/etc/bandit_pass/bandit5
/etc/bandit_pass/bandit26
/etc/bandit_pass/bandit24
/etc/bandit_pass/bandit12
/etc/bandit_pass/bandit28
/etc/bandit_pass/bandit2
/etc/bandit_pass/bandit10
/etc/bandit_pass/bandit31
/etc/bandit_pass/bandit16
/etc/bandit_pass/bandit17
/etc/bandit_pass/bandit7
/etc/bandit_pass/bandit9
/etc/bandit_pass/bandit18
/etc/bandit_pass/bandit3
/etc/bandit_pass/bandit33
/etc/bandit_pass/bandit25
/etc/bandit_pass/bandit4
/etc/bandit_pass/bandit19
/etc/bandit_pass/bandit6
/etc/bandit_pass/bandit11
/etc/bandit_pass/bandit1
/etc/bandit_pass/bandit22
/etc/bandit_pass/bandit27
/etc/bandit_pass/bandit14
$ cat /etc/bandit_pass/bandit33
tQdtbs5D5i2vJwkO8mEyYEyTL8izoeJ
```
