# Bandit Level 5 → Level 6

## Goal

Find a file somewhere under the `inhere` directory with the following properties:

- Human-readable
- Exactly 1033 bytes in size
- Not executable

## Commands Used

```bash
ls
cd inhere
find . -type f -size 1033c ! -executable
cat <path-to-file>