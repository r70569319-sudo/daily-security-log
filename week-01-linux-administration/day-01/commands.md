# Day 1 — Commands Practiced

## Navigation

| Command | Description | Example |
|---------|-------------|---------|
| `pwd` | Present working directory | `pwd` |
| `ls` | List files | `ls` |
| `ls -l` | Long format listing | `ls -l` |
| `ls -la` | Include hidden files | `ls -la` |
| `cd` | Change directory | `cd /home` |
| `cd ..` | Go up one level | `cd ..` |
| `cd ~` | Go to home directory | `cd ~` |

## File Operations

| Command | Description | Example |
|---------|-------------|---------|
| `cat` | Print file content | `cat readme` |
| `touch` | Create empty file | `touch file1.txt` |
| `chmod` | Change file permissions | `chmod 755 file1.txt` |
| `chown` | Change file owner | `chown user:group file1.txt` |

## Help

| Command | Description | Example |
|---------|-------------|---------|
| `--help` | Quick help for command | `ls --help` |
| `man` | Manual page | `man ls` |

## Permission Cheatsheet

| Number | Permission | Meaning |
|--------|-----------|---------|
| 7 | rwx | Read + Write + Execute |
| 6 | rw- | Read + Write |
| 5 | r-x | Read + Execute |
| 4 | r-- | Read only |
| 0 | --- | No permission |

**Example:** `chmod 755 file.txt` → Owner: rwx, Group: r-x, Others: r-x
