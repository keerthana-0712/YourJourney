# git status

The command:

```bash id="83f1cd"
git status
```

is one of the most frequently used Git commands.

It shows the current state of your project.

Developers use it daily to check:

* changed files
* staged files
* untracked files
* branch information

---

# What Does git status Do?

```bash id="87e40b"
git status
```

helps you understand:

> “What is happening inside the repository right now?”

It tells you:

* which files changed
* which files are ready for commit
* which files are not being tracked

---

# Why git status is Important

Before making commits, developers usually check:

```bash id="34a18b"
git status
```

because it helps avoid mistakes like:

* forgetting files
* committing wrong changes
* missing updates

This command acts like a project health checker.

---

# How to Use git status

Inside your Git repository, run:

```bash id="6dd12f"
git status
```

---

# Example Output

Example:

```txt id="k4n9pt"
On branch main

No commits yet

Untracked files:
  index.html
```

This means:

* repository is on `main` branch
* no commits exist yet
* `index.html` is not tracked by Git

---

# Understanding File States

Git mainly tracks files in different states.

---

## 1. Untracked Files

Files Git does not know about yet.

Example:

```txt id="e2v8rm"
index.html
style.css
```

These files were created but not added to Git.

---

## 2. Staged Files

Files ready for commit.

After running:

```bash id="9174c6"
git add .
```

Git moves files into the staging area.

---

## 3. Committed Files

Files already saved permanently in Git history.

---

# Real-World Understanding

Think of:

```bash id="49df03"
git status
```

like checking:

> “What work is pending before submitting an assignment?”

It helps developers stay organized.

---

# Common Situations

## After Creating New File

Git shows:

```txt id="z6m4qp"
Untracked files
```

---

## After Adding File

Git shows:

```txt id="r4q8vn"
Changes to be committed
```

---

## After Commit

Git may show:

```txt id="u7k3md"
nothing to commit, working tree clean
```

This means everything is saved properly.

---

# Most Common Beginner Mistake

Beginners often:

* make changes
* forget to check status
* accidentally miss files

Professional developers regularly use:

```bash id="72fe31"
git status
```

before commits and pushes.

---

# Beginner Tip

Use:

```bash id="0ff0c6"
git status
```

frequently while learning Git.

It helps you understand:

* what Git is tracking
* current project state
* workflow progress

---

# Real Workflow Example

Example Git workflow:

```txt id="5p8qvn"
Create File
     ↓
git status
     ↓
git add .
     ↓
git status
     ↓
git commit
```

You can clearly see how project state changes step by step.

---

# Simple Summary

```bash id="db76f0"
git status
```

helps developers:

* view repository state
* track changed files
* understand Git workflow
* avoid mistakes

It is one of the most important Git commands.

---

# Practice Task

✅ Create a new file

Example:

```txt id="h1m9vr"
index.html
```

✅ Run:

```bash id="d69f09"
git status
```

✅ Observe:

* untracked files
* repository state

---

# Next Step

Continue to:

```txt id="w8q2pm"
git-add.md
```
