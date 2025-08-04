# 🖥️ Git Bash Command Cheat Sheet

A beginner-friendly **Git Bash command reference** that covers essential **Git** and **Bash (Linux)** commands.  
This cheat sheet is perfect for developers working on Windows who use Git Bash for version control and terminal commands. <br>

Git Bash is a terminal that lets you run Git commands and Unix/Linux commands on Windows.
You can't realistically list all commands in a single message because:
1. Git has hundreds of commands and options.
2. Bash supports all Unix shell commands (ls, cd, mv, grep, etc.).

---

## 📌 Git Commands

### **Setup**
```bash
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
git config --list
```

### **Create/Clone***
```bash
git init
git clone <url>
```

### **Check Status**
```bash
git init
git clone <url>
```

### **Stage & Commit**
```bash
git add <file>
git add .
git commit -m "message"
```

### **Branches**
```bash
git branch
git branch <branch>
git checkout <branch>
git checkout -b <branch>
git merge <branch>
```

### **Remote**
```bash
git remote -v
git remote add origin <url>
git push -u origin main
git pull origin main
```

### **Undo**
```bash
git restore <file>
git reset HEAD <file>
git reset --hard
```

---

## **🐧 Bash Commands (in Git Bash)**

### ** Navigation**
```bash
pwd
ls
ls -la
cd <dir>
cd ..
```

### ** Files & Directories**
```bash
touch file.txt
mkdir newfolder
rm file.txt
rm -r folder
mv old.txt new.txt
cp file.txt copy.txt
```

### **Search**
```bash
grep "word" file.txt
find . -name "*.txt"
```

### **View & Edit**
```bash
cat file.txt
nano file.txt
less file.txt
```
---

## **Useful Extras**

```bash
clear
history
echo "Hello"
whoami
```

## 📜 License
This cheat sheet is open-source and free to use under the [MIT License](https://mit-license.org/).

## 📧 Contact
Abdullah Al Fahim | alfahim604@yahoo.com





