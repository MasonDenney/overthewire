# Bandit

## Intro
The following file contains notes I made while playing the Bandit wargame at:
https://overthewire.org/wargames/bandit/

Note that reconnected to the server as a different user for each level.

## Pre-0
https://overthewire.org/wargames/bandit/bandit0.html
```
https://overthewire.org/wargames/bandit/bandit0.html
```
bandit0

## 0
https://overthewire.org/wargames/bandit/bandit1.html
```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
ls
cat readme
```
boJ9jbbUNNfktd78OOpsqOltutMc3MY1

## 1
https://overthewire.org/wargames/bandit/bandit2.html
```bash
ssh bandit1@bandit.labs.overthewire.org -p 2220
ls
cat ./-
```
CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9

## 2
https://overthewire.org/wargames/bandit/bandit3.html
```bash
ssh bandit2@bandit.labs.overthewire.org -p 2220
ls
cat spaces\ in\ this\ filename
```
UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK

## 3
https://overthewire.org/wargames/bandit/bandit4.html
```bash
ssh bandit3@bandit.labs.overthewire.org -p 2220
cat inhere/.hidden
```
pIwrPrtPN36QITSp3EQaw936yaFoFgAB

## 4
https://overthewire.org/wargames/bandit/bandit5.html
```bash
ssh bandit4@bandit.labs.overthewire.org -p 2220
cd inhere
cat ./-file0*
cat ./-file07
```
koReBOKuIDDepwhWk7jZC0RTdopnAYKh

## 5
https://overthewire.org/wargames/bandit/bandit6.html
```bash
ssh bandit5@bandit.labs.overthewire.org -p 2220
cd inhere
find . -size 1033c
cat ./maybehere07/.file2
```
DXjZPULLxYr17uwoI01bNLQbtFemEgo7

## 6
https://overthewire.org/wargames/bandit/bandit7.html
```bash
ssh bandit6@bandit.labs.overthewire.org -p 2220
find / -size 33c -user bandit7 -group bandit6 2>/dev/null
cat /var/lib/dpkg/info/bandit7.password
```
HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs

## 7
https://overthewire.org/wargames/bandit/bandit8.html
```bash
ssh bandit7@bandit.labs.overthewire.org -p 2220
less data.txt
cat data.txt | grep millionth
```
cvX2JJa4CFALtqS87jk27qwqGhBM9plV

## 8
https://overthewire.org/wargames/bandit/bandit9.html
```bash
ssh bandit8@bandit.labs.overthewire.org -p 2220
sort data.txt | uniq -u
```
UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR

## 9
https://overthewire.org/wargames/bandit/bandit10.html
```bash
ssh bandit9@bandit.labs.overthewire.org -p 2220
cat data.txt | grep == -a
```
truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk

## 10
https://overthewire.org/wargames/bandit/bandit11.html
```bash
ssh bandit10@bandit.labs.overthewire.org -p 2220
cat data.txt | base64 -d
```
IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR

## 11
https://overthewire.org/wargames/bandit/bandit12.html
```bash
ssh bandit11@bandit.labs.overthewire.org -p 2220
cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'
```
5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu

## 12
https://overthewire.org/wargames/bandit/bandit13.html
```bash
ssh bandit12@bandit.labs.overthewire.org -p 2220
mkdir /tmp/me/ && cp data.txt /tmp/me/ && cd /tmp/me/ && xxd -r data.txt data.gz
file data.gz
gzip -d data.gz && bzip2 -d -q data && mv data.out data.gz && gzip -d data.gz && tar xf data
tar xf data5.bin && bzip2 -d -q data6.bin && tar xf data6.bin.out && mv data8.bin data8.gz && gzip -d data8.gz && cat data8
```
8ZjyCRiBWFYkneahHwxCv3wb2a1ORpYL

## 13
https://overthewire.org/wargames/bandit/bandit14.html
```bash
ssh bandit13@bandit.labs.overthewire.org -p 2220
ls -la
ssh bandit14@localhost -i sshkey.private
```
NO PASSWORD NEEDED IF USING SSH \
4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e

## 14
https://overthewire.org/wargames/bandit/bandit15.html
```bash
ssh bandit14@bandit.labs.overthewire.org -p 2220
cat /etc/bandit_pass/bandit14
```
4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e
```
nmap -v localhost -p 30000
telnet localhost 30000
```
BfMYroe26WYalil77FoDi9qh59eK5xNr

## 15
https://overthewire.org/wargames/bandit/bandit16.html
```bash
ssh bandit15@bandit.labs.overthewire.org -p 2220
man openssl-s_client
openssl s_client -connect localhost:30001
    BfMYroe26WYalil77FoDi9qh59eK5xNr
```
cluFn7wTiGryunymYOu4RcffSxQluehd

## 16
https://overthewire.org/wargames/bandit/bandit17.html
```bash
ssh bandit16@bandit.labs.overthewire.org -p 2220
nmap -v localhost -p 31000-32000
openssl s_client -connect localhost:31790
```
-----BEGIN RSA PRIVATE KEY-----
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
dxviW8+TFVEBl1O4f7HVm6EpTscdDxU+bCXWkfjuRb7Dy9GOtt9JPsX8MBTakzh3
vBgsyi/sN3RqRBcGU40fOoZyfAMT8s1m/uYv52O6IgeuZ/ujbjY=
-----END RSA PRIVATE KEY-----
```bash
vi /tmp/sshkey.private
ssh bandit17@localhost -i /tmp/sshkey.private
cat /etc/bandit_pass/bandit17
```
xLYVMN9WE5zQ5vHacb0sZEVqbrp7nBTn

## 17
https://overthewire.org/wargames/bandit/bandit18.html
```bash
ssh bandit17@bandit.labs.overthewire.org -p 2220
diff passwords.old passwords.new
```
kfBf3eYk5BPBRzwjqutbbfE887SVc5Yd

## 18
https://overthewire.org/wargames/bandit/bandit19.html
```bash
ssh bandit18@bandit.labs.overthewire.org -p 2220 cat readme
```
IueksS7Ubh8G3DCwVzrTd8rAVOwq3M5x

## 19
https://overthewire.org/wargames/bandit/bandit20.html
```bash
ssh bandit19@bandit.labs.overthewire.org -p 2220
./bandit20-do cat /etc/bandit_pass/bandit20
```
GbKksEFF4yrVs6il55v6gwY5aVje5f0j

## 20
https://overthewire.org/wargames/bandit/bandit21.html \
Important to note that the password is within the given binary
```bash
ssh bandit20@bandit.labs.overthewire.org -p 2220
cat /etc/bandit_pass/bandit20 | nc -l localhost -p 33033
bg
./suconnect 33033
```
gE269g2h3mw3pwgrj0Ha9Uoqen1c9DGr

## 21
https://overthewire.org/wargames/bandit/bandit22.html
```bash
ssh bandit21@bandit.labs.overthewire.org -p 2220
cat /etc/cron.d/cronjob_bandit22
cat /usr/bin/cronjob_bandit22.sh
cat /tmp/t7O6lds9S0RqQh9aMcz6ShpAoZKF7fgv
```
Yk7owGAcWjwMVRwrTesJEwB7WVOiILLI

## 22
https://overthewire.org/wargames/bandit/bandit23.html
```bash
ssh bandit22@bandit.labs.overthewire.org -p 2220
cat /etc/cron.d/cronjob_bandit23
cat /usr/bin/cronjob_bandit23.sh
echo I am user bandit23 | md5sum | cut -d ' ' -f 1
cat /tmp/8ca319486bfbbc3663ea0fbe81326349
```
jc1udXuA1tiHqjIsL8yaapX5XIAI6i0n

## 23
https://overthewire.org/wargames/bandit/bandit24.html
```bash
ssh bandit23@bandit.labs.overthewire.org -p 2220
cat /usr/bin/cronjob_bandit24.sh
vi /tmp/m.sh
    #!/bin/bash
    cp /etc/banditpass/bandit24 /tmp/ans.txt
    chmod 777 /tmp/ans.txt
chmod 777 /tmp/m.sh
cp /tmp/m.sh /var/spool/bandit24
cat /tmp/ans.txt
```
UoMYTrfrBFHyQXmg6gzctqAwOmw1IohZ

## 24
https://overthewire.org/wargames/bandit/bandit25.html
```bash
ssh bandit24@bandit.labs.overthewire.org -p 2220
#!/bin/bash 
for first in {0..9}; do
#echo "$first "
for second in {0..9}; do
#echo "$second "
for third in {0..9}; do
#echo "$third "
for fourth in {0..9}; do
    #echo "$forth "
    echo "$first$second$third$fourth"
    result="$(echo "UoMYTrfrBFHyQXmg6gzctqAwOmw1IohZ $first$second$third$fourth" | nc -w 1 localhost 30002)"
    if [[ ! $result == *"Wrong"* ]]; then
        echo $result > /tmp/ans24.txt
        break
    fi  
done
done
done
done

2588
```
uNG9O58gUE7snukf3bvZ0rxhtnjzSGzG

## 25
https://overthewire.org/wargames/bandit/bandit26.html
```bash
ssh bandit25@bandit.labs.overthewire.org -p 2220
cat /etc/passwd
cat /usr/bin/showtest
man more
ssh bandit26@localhost -i bandit26.sshkey
v
:e /etc/bandit_pass/bandit26
```
SSH KEY GIVEN

5czgV9L3Xx8JPOyRbXh6lQbmIOWvPT6Z

## 26
https://overthewire.org/wargames/bandit/bandit27.html
```bash
ssh bandit26@bandit.labs.overthewire.org -p 2220
ssh bandit26@localhost -i bandit26.sshkey
v
:e /etc/bandit_pass/bandit26
```
5czgV9L3Xx8JPOyRbXh6lQbmIOWvPT6Z
```
:set shell=/bin/bash
:shell
./bandit27-do cat /etc/bandit_pass/bandit27
```
3ba3118a22e93127a4ed485be72ef5ea

## 27
https://overthewire.org/wargames/bandit/bandit28.html
```bash
ssh bandit27@bandit.labs.overthewire.org -p 2220
mkdir /tmp/m28
cd /tmp/m28
git clone ssh://bandit27-git@localhost/home/bandit27-git/repo.git
cd repo
cat README
```
0ef186ac70e04ea33b4c1853d2526fa2

## 28
https://overthewire.org/wargames/bandit/bandit29.html
```bash
ssh bandit28@bandit.labs.overthewire.org -p 2220
mkdir /tmp/m29
cd /tmp/m29
git clone ssh://bandit28-git@localhost/home/bandit28-git/repo
cd repo
cat README.md
git log -p
```
bbc96594b4e001778eee9975372716b2

## 29
https://overthewire.org/wargames/bandit/bandit30.html
```bash
ssh bandit29@bandit.labs.overthewire.org -p 2220
mkdir /tmp/m30
cd /tmp/m30
git clone ssh://bandit29-git@localhost/home/bandit29-git/repo
cd repo
cat README.md
git log -p
git branch -a
git checkout dev
git log -p
```
5b90576bedb2cc04c86a9e924ce42faf

## 30
https://overthewire.org/wargames/bandit/bandit31.html
```bash
ssh bandit30@bandit.labs.overthewire.org -p 2220
git tag
git show secret
```
47e603bb428404d265f59c42920d81e5

## 31
https://overthewire.org/wargames/bandit/bandit32.html
```bash
ssh bandit31@bandit.labs.overthewire.org -p 2220
echo 'May I come in?' > key.txt
rm .gitignore
git add -A
git commit
git push
```
56a9bf19c63d650ce78e6ec0354ee45e

## 32
https://overthewire.org/wargames/bandit/bandit33.html
```bash
ssh bandit32@bandit.labs.overthewire.org -p 2220
$0
cat /etc/bandit_pass/bandit33
```
c9c3199ddf4121b10cf581a98d51caee

## 33
https://overthewire.org/wargames/bandit/bandit34.html
```bash
ssh bandit33@bandit.labs.overthewire.org -p 2220
cat README.txt
```
NO MORE LEVELS

