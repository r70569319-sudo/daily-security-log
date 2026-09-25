# Day 1 — Linux Basics & First Steps

**Date:** 25 September 2026
**Time Spent:** 3 hours
**Topic:** Linux fundamentals, CLI basics, permissions, Bandit Level 0-2

---

## 🎯 Today's Goal

- Understand Linux file system structure
- Practice Basic commands (`pwd`, `ls`, `cd`, `cat`)
- Solve OverTheWire Bandit Level 0-2
- Start GitHub portfolio

---

## 📚 Theory Covered

- **TryHackMe:** Linux Fundamentals Part 1 — Task 1, 2, 3
- **Book:** Linux Basics for Hackers — Chapter 1
- **Concepts:** Linux file system structure, root, home directory, shell, terminal, case sensitivity

---

## 🛠️ Practical Work

- Basic commands drill: `pwd`, `ls -la`, `cd`, `cat`, `--help`, `man`
- File permissions: `chmod 755`, `644`, `700`
- OverTheWire Bandit Level 0 → 1, Level 1 → 2

See:
- [`commands.md`](commands.md) — Commands practiced today
- [`notes.md`](notes.md) — Theory notes
- [`screenshots/`](screenshots/) — Terminal screenshots

---

## 🧠 What I Learned

1. Linux file system start from root `/`  and each directory have its own specific purpose (`/etc` for config, `/bin` for binaries, etc.)
2. Linux is case-sensitive — `File.txt` and `file.txt` are different.
3. `ls -la` shows hidden files (which starts from `.`).
4. In Bandit Level 1 `-` (dash) filename reads with the help of `cat ./-` because `-` treat as a command flag.
5. Permissions set in the form of numbers: r=4, w=2, x=1. that's why 755 = rwxr-xr-x.

---

## ⚠️ Challenges Faced

-In Bandit Level 1 confused with `-` filename. Solution: Use `cat ./-`.
-Understanding the columns of `ls -la` was time taking (permissions, links, owner, group, size, date, name).

---

## ✅ Checklist

- [x] THM Linux Fundamentals Part 1 — Task 1, 2, 3
- [x] Book Chapter 1 read
- [x] Basic commands drill
- [x] Bandit Level 0 → 1 solved
- [x] Bandit Level 1 → 2 solved
- [x] File permissions drill
- [x] GitHub repo updated
