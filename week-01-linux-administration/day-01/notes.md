# Day 1 — Theory Notes

## Linux File System Structure

/ (root).
├── /root → Root user's home directory.

├── /etc → Configuration files

├── /home → User home directories

├── /bin → Application binaries (ls, cat, cp)

├── /lib → Shared libraries

├── /mnt → Mounted filesystems

├── /media → Removable media (USB, CD)

├── /var → Variable data (logs, spool)

└── /tmp → Temporary files


## Key Terminology

- **Binaries** — Executable files (Windows .exe equivalent)
- **Case Sensitivity** — `File.txt` ≠ `file.txt`
- **Directory** — Folder
- **Home Directory** — User's personal space (`/home/username`)
- **Root** — Linux superuser (UID 0)
- **Shell** — Command interpreter (Bash, Zsh)
- **Terminal** — Interface to use the shell

## File Permissions

Format: `-rwxr-xr-x`
- First char: file type (`-` file, `d` directory)
- Next 3: owner permissions
- Next 3: group permissions
- Last 3: others permissions

| Symbol | Meaning | Value |
|--------|---------|-------|
| r | Read | 4 |
| w | Write | 2 |
| x | Execute | 1 |
| - | No permission | 0 |

## OverTheWire Bandit — What I Learned

- SSH connection: `ssh bandit0@bandit.labs.overthewire.org -p 2220`
- `ls -al` shows hidden files (starting with `.`)
- Tricky filename `-` can be read using `cat ./-`
