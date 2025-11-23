## 🛠️ Quick Lab Instructions — 2.1 Command Line Basics

---

>💬 **Tip:** Paste this study guide into ChatGPT and ask for **more instructions** by specifying:  
>- “Provide step-by-step lab instructions for this objective.”  
>- “Include which Linux distro to use (Debian/Ubuntu or RHEL/Fedora).”  
>- “Show examples of installing, verifying, and managing desktop and server applications.”  
>- “Include minimal command-line practice for package management and development tools.”  
>- “Focus only on what is most important for passing the LPI Linux Essentials exam.”  

>This will prompt ChatGPT to give **practical, exam-focused lab steps** for each section.

---

### 1️⃣ Open the Terminal 🖥️
- GUI: open **Terminal app** (`Ctrl+Alt+T`)  
- Virtual console: `Ctrl+Alt+F1-F6`  
- Observe shell prompt (`$` for user, `#` for root)

---

### 2️⃣ Explore Basic Commands
- **Print text**: `echo "Hello World"`  
- **Check your shell**: `echo $SHELL`  
- **View environment variables**: `echo $PATH`  
- **Check command type**: `type ls`, `type echo`  
- **Review history**: `history | tail`  

---

### 3️⃣ Work with Variables 🌐
- Create a local variable: `MYVAR="Test"`  
- Display variable: `echo $MYVAR`  
- Export variable: `export MYVAR="Test"` → available to child processes  
- Experiment with environment variables: `echo $HOME`, `echo $USER`  

---

### 4️⃣ Practice Quoting
- Single quotes (literal): `echo '$MYVAR'` → prints `$MYVAR`  
- Double quotes (expand variables): `echo "$MYVAR"` → prints `Test`  
- Command substitution:  
  - Backticks: ``echo `date` ``  
  - Modern: `echo $(date)` → prints current date/time  

---

### ⚡ Notes
- Focus on **understanding shell behavior**, variable usage, and quoting  
- Observe **output changes** when using different quotes or command substitution  
- Labs are about **exploration and familiarization**, not complex scripting
