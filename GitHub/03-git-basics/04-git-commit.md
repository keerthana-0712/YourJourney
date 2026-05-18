# git commit

The command:

```bash id="5dbbea"
git commit
```

is used to save staged changes permanently into Git history.

In simple words:

> A commit is like saving a checkpoint of your project.

Developers use commits to track project progress step by step.

---

# Why git commit is Important

Commits help developers:

* save project versions
* track changes over time
* restore old work
* understand project history
* collaborate safely

Without commits, Git cannot remember project changes properly.

---

# Understanding the Workflow

Basic Git workflow:

```txt id="m9v2qp"
Create or Edit File
        ↓
git add
        ↓
git commit
```

After staging files using:

```bash id="9c3cfa"
git add
```

developers create commits.

---

# What Does a Commit Contain?

A commit usually contains:

* file changes
* commit message
* author information
* timestamp

Git stores this information in project history.

---

# How to Create a Commit

Basic syntax:

```bash id="f87a8d"
git commit -m "Your commit message"
```

Example:

```bash id="7d6c59"
git commit -m "Added homepage design"
```

---

# What Does -m Mean?

```txt id="g8m4qn"
-m
```

means:

> message

It allows developers to write a short description for the commit.

---

# Why Commit Messages Matter

Commit messages explain:

* what changed
* why changes were made

Good commit messages make project history easier to understand.

---

# Good Commit Message Examples

```txt id="f1m8vk"
Added login page
Fixed navbar bug
Updated README documentation
Created contact form
```

---

# Bad Commit Message Examples

```txt id="t6v2qp"
update
changes
done
final
```

These messages are unclear and unprofessional.

---

# Example Workflow

## Step 1 — Create File

Example:

```txt id="p7m4vq"
index.html
```

---

## Step 2 — Add File

Run:

```bash id="b9f73b"
git add index.html
```

---

## Step 3 — Commit Changes

Run:

```bash id="d86835"
git commit -m "Added index.html file"
```

---

# Example Output

You may see:

```txt id="x4q7pn"
1 file changed
create mode 100644 index.html
```

This means the commit was successful.

---

# Real-World Understanding

Think of commits like:

> saving milestones in a project.

Example:

* project started
* homepage completed
* login feature added
* bugs fixed

Each commit represents progress.

---

# Why Developers Make Multiple Commits

Instead of one huge commit, developers create:

* small
* organized
* meaningful

commits.

This helps:

* debugging
* teamwork
* project tracking

---

# Common Beginner Mistakes

## Forgetting git add

Beginners sometimes run:

```bash id="75d2e8"
git commit
```

without staging files first.

Git only commits staged changes.

---

## Poor Commit Messages

Avoid unclear messages like:

```txt id="v5q8pn"
done
updated
changes
```

Professional commit messages improve readability.

---

# Helpful Command

To view commit history:

```bash id="77e36f"
git log
```

You will learn this command later.

---

# Beginner Tip

A good beginner habit:

```txt id="r4m8vq"
Make small commits regularly
```

instead of:

```txt id="g2q7mk"
one huge commit after many changes
```

This keeps project history clean.

---

# Simple Summary

```bash id="6382a6"
git commit
```

helps developers:

* save project progress
* track changes
* create version history
* organize development workflow

Commits are the backbone of Git history.

---

# Practice Task

✅ Create or edit a file

✅ Run:

```bash id="acb7fd"
git add .
```

✅ Run:

```bash id="2f1481"
git commit -m "My first commit"
```

✅ Observe the commit output

---

# Next Step

Continue to:

```txt id="m6q3vp"
git-push.md
```
