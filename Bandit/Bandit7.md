# Bandit Level 6 → Level 7
## Objective

Find a file owned by user bandit7 and group bandit6.

## Commands Used
find / -user bandit7 -group bandit6 -size 33c 2>/dev/null
cat /var/lib/dpkg/info/bandit7.password

## Explanation

The find command filters by owner, group, and size.

## Result

Learned advanced file searching.


Flag:morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj
