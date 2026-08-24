# Bandit Level 6 → Level 7

## Goal

Find the password for the next level.

The password is stored somewhere on the server in a file with the following properties:

- Owned by user `bandit7`
- Owned by group `bandit6`
- Exactly 33 bytes in size

## Commands Used

```bash
find / -user bandit7 -group bandit6 -size 33c 2>/dev/null
cat <path-to-file>