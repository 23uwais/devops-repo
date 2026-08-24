# Bandit Level 9 → Level 10

## Goal

Find the password for the next level.

The password is stored in `data.txt` among several lines of text. It is the only human-readable line containing the `=` character.

## Commands Used

```bash
ls
strings data.txt | grep "="