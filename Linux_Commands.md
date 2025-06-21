# 🐧 Linux Essentials

## 📌 Overview

Linux is a Unix-like OS with popular distributions like:

* Ubuntu
* CentOS

---

## 🖥️ Shell Scripts

Text files with sequential shell commands.

### 🧪 Example

```bash
#!/bin/bash
echo "Hello, World!"
```

Run with:

```bash
bash script.sh
```

---

## 🔁 REPL

**REPL**: Read → Evaluate → Print → Loop
🧪 Example: Python console

```bash
python3
>>> print("Hi")
Hi
```

---

## 🆘 Help

```bash
<command> --help
```

---

# 📂 Terminal Commands

## 🔍 Basics

```bash
pwd       # Current directory
clear     # Clear screen
ls        # List contents
ls -lha   # List all with details
```

---

## 🧭 Directory Ops

```bash
mkdir name     # Make folder
rmdir name     # Remove empty folder
```

### 🧪 Example

```bash
mkdir test
cd test
```

---

## 📄 File Ops

```bash
touch file     # New file
cat file       # Show content
rm file        # Delete file
```

### 🧪 Example

```bash
touch notes.txt
cat notes.txt
rm notes.txt
```

---

## 📌 cd (Change Directory)

```bash
cd folder      # Enter folder
cd ..          # Up one level
cd ~           # Home
cd -           # Previous dir
```

---

## 📁 Directory Tree

```
~
└── Projects/Finance/FIRE/Plans
```

```bash
cd ~/Projects/Finance/FIRE/Plans
cd ../..   # Back up
cd ~       # Home
```

---

## 🔀 Piping

```bash
command1 | command2
```

### 🧪 Examples

```bash
ls | grep report           # Filter
ls | grep report | wc -l   # Count matches
ls > dump.txt              # Save output
```

---

## 📋 Copy & Move

```bash
cp file.txt file-copy.txt       # Copy file
cp -r folder folder-copy        # Copy folder
mv old.txt new.txt              # Rename
mv file.txt folder/             # Move
```

### 🧪 Example

```bash
cp notes.txt backup.txt
mv backup.txt archive/
```

---

## 💡 Tips

* `~` = home dir, `/` = root dir
* `Tab` = auto-complete
* Use quotes: `cd "My Folder"`
