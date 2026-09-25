# Day 1 — Linux Basics & First Steps

**Date:** 25 September 2026
**Time Spent:** 3 hours
**Topic:** Linux fundamentals, CLI basics, permissions, Bandit Level 0-2

---

## 🎯 Aaj Ka Goal

- Linux file system structure samajhna
- Basic commands (`pwd`, `ls`, `cd`, `cat`) seekhna
- OverTheWire Bandit Level 0-2 solve karna
- GitHub portfolio start karna

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

1. Linux file system root `/` se start hota hai aur har directory ka apna specific purpose hai (`/etc` for config, `/bin` for binaries, etc.)
2. Linux case-sensitive hai — `File.txt` aur `file.txt` alag hain.
3. `ls -la` hidden files bhi dikhata hai (jo `.` se start hoti hain).
4. Bandit Level 1 mein `-` (dash) filename ko `cat ./-` se padha jata hai kyunke `-` ko command flag samjha jata hai.
5. Permissions numbers mein hoti hain: r=4, w=2, x=1. Isliye 755 = rwxr-xr-x.

---

## ⚠️ Challenges Faced

- Bandit Level 1 mein `-` filename se confuse hua. Solution: `cat ./-` use kiya.
- `ls -la` ke columns samajhne mein thoda time laga (permissions, links, owner, group, size, date, name).

---

## ✅ Checklist

- [x] THM Linux Fundamentals Part 1 — Task 1, 2, 3
- [x] Book Chapter 1 read
- [x] Basic commands drill
- [x] Bandit Level 0 → 1 solved
- [x] Bandit Level 1 → 2 solved
- [x] File permissions drill
- [x] GitHub repo updated
