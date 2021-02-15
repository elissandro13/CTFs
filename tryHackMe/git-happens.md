# Git Happens

#### Scan 
$nmap -A -T$ 10.10.19.155
Found port 80 open and git repository

#### Git Dump
Transform the git log in the website into local directory
$git-dump ip

#### Git Log
Commit 39er08 shows login pagen before cryptographing the password

#### Search details of this commit looking for password
$git show 39er08 | grep passqord

Password found, it's the flag. 
