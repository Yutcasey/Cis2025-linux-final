# CIS 2023 – Linux – Final Project

This repository demonstrates creating and maintaining a Git repository from the Linux command line. It includes a Bash script that prints numbers **1 through 50** to the terminal.

## Files
- `print_1_to_50.sh` — Bash script that prints 1..50 (supports optional `--reverse`)
- `README.md` — Project description and usage instructions
- `.gitignore` — Ignore editor/OS artifacts

## Usage
```bash
chmod +x print_1_to_50.sh
./print_1_to_50.sh
# Optional reverse order:
./print_1_to_50.sh --reverse
```

## Git Quick Start
```bash
git init
git add print_1_to_50.sh README.md .gitignore
git commit -m "Initial commit"
```
