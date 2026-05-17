# How to Configure Git

After installing Git, you need to configure it on your computer.

Git configuration helps Git know:

* your name
* your email
* who is making commits

This information appears in your project history.

---

# Why Git Configuration is Important

Every time you make a commit, Git stores:

* author name
* author email
* commit message

Without configuration, Git may not work properly for commits.

---

# Step 1 — Open Terminal

Open:

* VS Code Terminal
* Command Prompt
* PowerShell
* Terminal

You will run Git commands here.

---

# Step 2 — Configure Your Username

Run this command:

```bash id="39bb9d"
git config --global user.name "Your Name"
```

Example:

```bash id="b86db7"
git config --global user.name "Keerthana Salla"
```

This sets your Git username globally on your computer.

---

# Step 3 — Configure Your Email

Run this command:

```bash id="a49c11"
git config --global user.email "your-email@example.com"
```

Example:

```bash id="2a20b0"
git config --global user.email "keerthana@example.com"
```

Important:
Use the same email connected to your GitHub account if possible.

---

# What Does --global Mean?

```txt id="8r3vqm"
--global
```

means:

> apply this configuration to all Git projects on your computer.

Without `--global`, configuration works only for one project.

---

# Step 4 — Check Your Configuration

Run:

```bash id="d4c4b6"
git config --list
```

This shows your Git configuration settings.

You should see:

* username
* email
* other Git settings

---

# Example Output

```txt id="h6m2tk"
user.name=Keerthana Salla
user.email=keerthana@example.com
```

This means Git is configured successfully.

---

# Why Email Matters in GitHub

GitHub uses your email to:

* connect commits to your account
* show contribution history
* track activity

Correct email configuration is important.

---

# Beginner Tip

Do not worry if commands look confusing initially.

Git commands become easier with practice.

Start slowly and experiment regularly.

---

# Common Beginner Mistakes

## Wrong Email

Using a different email than GitHub account email may prevent contributions from appearing correctly.

---

## Typing Errors

Small typing mistakes in commands can cause errors.

Always type carefully.

---

# Helpful Command

To check your Git version:

```bash id="a0cb0c"
git --version
```

To check configuration:

```bash id="7c70c9"
git config --list
```

These commands are used frequently by developers.

---

# Real-World Understanding

Think of Git configuration like:

> setting your identity before starting work.

It tells Git:

* who you are
* who created the changes

---

# Simple Summary

Git configuration helps:

* identify commits
* connect activity with GitHub
* prepare your system for development

This is an important setup step before creating repositories.

---

# Practice Task

✅ Configure your username
✅ Configure your email
✅ Run:

```bash id="c4e8fb"
git config --list
```

✅ Verify your configuration

---

# Next Step

Continue to:

```txt id="z8q2ph"
test-git-installation.md
```
