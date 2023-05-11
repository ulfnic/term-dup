# term-dup

Use [exec-in-term](https://github.com/ulfnic/exec-in-term) to open or execute a command in multiple interactive terminal windows in the current directory.

## Syntax
```bash
dup [NUMBER] [COMMAND]    Open NUMBER terminals and run COMMAND in each
dup [NUMBER]              Open NUMBER terminals
dup [COMMAND]             Open one terminal and run COMMAND
```

## Installation
```bash
# Install to /usr/local/bin
cd /usr/local/bin
sudo wget https://raw.githubusercontent.com/ulfnic/term-dup/main/dup
sudo chmod +x ./dup

# Test run
dup 'echo "test"'

# Satisfy dependencies if prompted to do so.
```

## Dependencies
- [exec-in-term](https://github.com/ulfnic/exec-in-term)

## License
Licensed under Zero-Clause BSD (0BSD). See LICENSE for details.
