# Bandit Level 19 → Level 20
## Objective

Use a setuid binary.

## Commands Used
./bandit20-do cat /etc/bandit\_pass/bandit20

## Explanation

A SUID binary allowed execution with higher privileges.

Using it, I read the password file directly.

## Result

Learned privilege escalation basics.

Flag:0qXahG8ZjOVMN9Ghs7iOWsCfZyXOUbYO


