# Bandit

## Intro
The following file contains notes I made while playing the Bandit wargame at:
https://overthewire.org/wargames/bandit/

Note that reconnected to the server as a different user for each level.

## pre-0
```
https://overthewire.org/wargames/bandit/bandit0.html
```
bandit0

## 0
```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
ls
cat readme
```
boJ9jbbUNNfktd78OOpsqOltutMc3MY1

## 1
```bash
ssh bandit1@bandit.labs.overthewire.org -p 2220
ls
cat ./-
```
CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9

## 2
```bash
ssh bandit2@bandit.labs.overthewire.org -p 2220
ls
cat spaces\ in\ this\ filename
```
UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK

## 3
```bash
ssh bandit3@bandit.labs.overthewire.org -p 2220
cat inhere/.hidden
```
pIwrPrtPN36QITSp3EQaw936yaFoFgAB

## 4
```bash
ssh bandit4@bandit.labs.overthewire.org -p 2220
cd inhere
cat ./-file0*
cat ./-file07
```
koReBOKuIDDepwhWk7jZC0RTdopnAYKh

## 5
```bash
ssh bandit5@bandit.labs.overthewire.org -p 2220
cd inhere
find . -size 1033c
cat ./maybehere07/.file2
```
DXjZPULLxYr17uwoI01bNLQbtFemEgo7

## 6
```bash
ssh bandit6@bandit.labs.overthewire.org -p 2220
find / -size 33c -user bandit7 -group bandit6 2>/dev/null
cat /var/lib/dpkg/info/bandit7.password
```
HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs

## 7
```bash
ssh bandit7@bandit.labs.overthewire.org -p 2220
less data.txt
cat data.txt | grep millionth
```
cvX2JJa4CFALtqS87jk27qwqGhBM9plV

## 8
```bash
ssh bandit8@bandit.labs.overthewire.org -p 2220
sort data.txt | uniq -u
```
UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR

## 9
```bash
ssh bandit9@bandit.labs.overthewire.org -p 2220
cat data.txt | grep == -a
```
truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk
## 10
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
```bash
ssh bandit12@bandit.labs.overthewire.org -p 2220
```

## 13
```bash
ssh bandit13@bandit.labs.overthewire.org -p 2220
```

## 14
```bash
ssh bandit14@bandit.labs.overthewire.org -p 2220
```

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

