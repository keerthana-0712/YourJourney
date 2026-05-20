# git log

The command:

```bash id="f80bc9"
git log
```

is used to view the history of commits in a Git repository.

In simple words:

> git log shows the history of saved project changes.

Developers use it to:

* track project progress
* view previous commits
* understand project history
* debug problems
* review development activity

---

# Why git log is Important

Every commit made in Git is stored permanently in project history.

Using:

```bash id="0a2df9"
git log
```

developers can see:

* who made changes
* what changes were made
* when changes happened

This is extremely useful in real-world projects.

---

# Basic Syntax

```bash id="2b5ff5"
git log
```

Run this command inside your Git repository.

---

# Example Output

Example:

```txt id="u3m8vq"
commit 7f3c9a...
Author: Keerthana Salla
Date: Mon May 18

Added homepage design
```

---

# Understanding git log Output

---

## Commit ID

Example:

```txt id="w8q2vn"
7f3c9a...
```

This is a unique identifier for the commit.

Every commit has its own unique ID.

---

## Author

Shows:

* who created the commit

Example:

```txt id="d7m4qp"
Author: Keerthana Salla
```

---

## Date

Shows:

* when the commit was created

---

## Commit Message

Shows:

* what changes were made

Example:

```txt id="m5v8qp"
Added homepage design
```

---

# Real-World Understanding

Think of:

```bash id="2f1b85"
git log
```

like:

> viewing the timeline/history of your project.

It helps developers understand how a project evolved over time.

---

# Why Developers Use git log

Developers use:

```bash id="d9c93d"
git log
```

to:

* review progress
* debug issues
* track feature development
* understand team activity
* restore old work

It is one of the most useful Git commands.

---

# Useful Variations

---

## Short One-Line History

```bash id="8db06c"
git log --oneline
```

Example output:

```txt id="t4q7vn"
a1b2c3 Added login page
d4e5f6 Fixed navbar bug
```

This gives a cleaner, shorter history view.

---

## Limited Commit History

```bash id="596dfd"
git log -3
```

Shows only the latest 3 commits.

---

# Common Beginner Mistakes

## Panic Seeing Long Output

Beginners sometimes get confused because:

```bash id="c8a34e"
git log
```

can display a lot of information.

Use:

```bash id="a4410d"
q
```

to exit the log screen.

---

## Poor Commit Messages

Bad commit messages make:

```bash id="0f2b95"
git log
```

hard to understand.

Good commit messages improve project readability.

---

# Helpful Beginner Workflow

Good workflow:

```txt id="y2m8vq"
Make Changes
     ↓
git add
     ↓
git commit
     ↓
git log
```

This helps beginners understand commit history clearly.

---

# Real Team Usage

In companies, developers use:

```bash id="e61d3f"
git log
```

to:

* review development history
* investigate bugs
* understand project changes
* track team contributions

---

# Beginner Tip

After every commit, try running:

```bash id="89c2dc"
git log --oneline
```

This helps you:

* understand commits better
* track your progress
* become comfortable with Git history

---

# Simple Summary

```bash id="3f0f9a"
git log
```

helps developers:

* view commit history
* track project changes
* understand development progress
* debug repositories

It acts like the history timeline of a project.

---

# Practice Task

✅ Create multiple commits

✅ Run:

```bash id="58c8cf"
git log
```

✅ Run:

```bash id="10c93f"
git log --oneline
```

✅ Observe commit history

---

# Next Step

Continue to:

```txt id="n7q4vp"
git-diff.md
```
