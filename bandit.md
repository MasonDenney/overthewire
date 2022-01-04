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
NO PASSWORD NEEDED IF USING SSH
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
```bash
ssh bandit15@bandit.labs.overthewire.org -p 2220
```

## 16
```bash
ssh bandit16@bandit.labs.overthewire.org -p 2220
```

## 17
```bash
ssh bandit17@bandit.labs.overthewire.org -p 2220
```

## 18
```bash
ssh bandit18@bandit.labs.overthewire.org -p 2220
```

## 19
```bash
ssh bandit19@bandit.labs.overthewire.org -p 2220
```

