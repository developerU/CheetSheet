# CheetSheet
Hack The Box用に作成中。
## 手順
- [調査](#Investigation)
  - [Nmap](#nmap)
  - [Gobuster](#gobuster)

## Nmap
```
nmap -sC -sV -oN <output filename> <target ip>
```
## Gobuster
```
gobuster dir -u <url> -w /usr/share/wordlists/dirbuster/directory-list-lowercase-2.3-medium.txt -o <output filename>
```
