# How to Test Git Installation

After installing and configuring Git, it is important to test whether Git is working correctly on your computer.

This helps confirm that:

* Git is installed properly
* terminal can access Git
* configuration works correctly

Testing your setup is a good development habit.

---

# Step 1 — Open Terminal

Open:

* VS Code Terminal
* Command Prompt
* PowerShell
* macOS Terminal
* Linux Terminal

You will run Git commands here.

---

# Step 2 — Check Git Version

Run this command:

```bash id="a90b34"
git --version
```

If Git is installed correctly, you will see output similar to:

```txt id="u2v8mc"
git version 2.xx.x
```

This means Git is successfully installed.

---

# Why This Command is Important

The command:

```bash id="7c0f6a"
git --version
```

checks whether:

* Git exists on your computer
* terminal recognizes Git commands

It is usually the first command developers run after installation.

---

# Step 3 — Check Git Configuration

Run:

```bash id="dd3a2e"
git config --list
```

You should see:

* username
* email
* Git settings

Example:

```txt id="t9k4pz"
user.name=Keerthana Salla
user.email=keerthana@example.com
```

This confirms Git configuration is working properly.

---

# Step 4 — Create a Test Folder

Create a folder anywhere on your computer.

Example:

```txt id="h3m6qy"
test-project
```

Open this folder in VS Code.

---

# Step 5 — Initialize Git

Inside terminal, run:

```bash id="3d6b8a"
git init
```

This command initializes Git inside your project folder.

If successful, you may see:

```txt id="k8v1nd"
Initialized empty Git repository
```

This means Git is now tracking the folder.

---

# What Does git init Do?

```bash id="fcb3d2"
git init
```

creates a hidden `.git` folder inside your project.

This folder stores:

* project history
* commits
* branches
* Git configuration

It turns a normal folder into a Git repository.

---

# Step 6 — Check Git Status

Run:

```bash id="7b02a5"
git status
```

This command shows:

* tracked files
* untracked files
* current branch
* project status

This is one of the most commonly used Git commands.

---

# Example Output

```txt id="y5m1qt"
On branch main

No commits yet
```

This means Git is working correctly.

---

# Common Beginner Errors

## Error: “git is not recognized”

Possible reasons:

* Git not installed properly
* terminal restart required
* PATH issue

Solution:

* restart terminal
* reinstall Git if needed

---

## Confusion About Terminal

Beginners often feel nervous using terminal commands.

That is completely normal.

With practice, terminal usage becomes easy and fast.

---

# Beginner Tip

Do not try to memorize all commands immediately.

Instead:

* understand purpose
* practice slowly
* repeat regularly

Git becomes easier through practical usage.

---

# Simple Summary

Testing Git installation helps verify:

* Git is installed
* configuration works
* repositories can be created
* terminal setup is successful

This confirms your system is ready for Git and GitHub development.

---

# Practice Task

✅ Run:

```bash id="08a9f1"
git --version
```

✅ Run:

```bash id="aafc4f"
git config --list
```

✅ Create a test folder
✅ Run:

```bash id="6b7c91"
git init
```

✅ Run:

```bash id="ee6f34"
git status
```

---

# Next Step

Continue to:

```txt id="d4m9kp"
connect-github-with-git.md
```
