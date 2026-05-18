
# git add

The command:

```bash id="3cf11e"
git add
```

is used to move files into the:

> staging area

before creating a commit.

In simple words:
`git add` tells Git:

> “I want to include these changes in my next commit.”

---

# Why git add is Important

Git does not automatically save every file change.

Developers first choose:

* which files to include
* which changes to save

This gives more control over project history.

---

# Understanding the Workflow

Basic Git workflow:

```txt id="y7m2qp"
Create or Edit File
        ↓
git add
        ↓
git commit
```

`git add` comes before committing changes.

---

# What is the Staging Area?

The staging area is a temporary preparation zone.

Think of it like:

> selecting files before final submission.

Files added using:

```bash id="2c4d0a"
git add
```

become ready for commit.

---

# Common Ways to Use git add

---

## Add Specific File

```bash id="ff0d93"
git add index.html
```

This stages only:

```txt id="y5v8mk"
index.html
```

---

## Add Multiple Files

```bash id="ba7b43"
git add index.html style.css
```

This stages multiple files together.

---

## Add All Files

```bash id="dbdc22"
git add .
```

The dot (`.`) means:

> add everything in the current project folder.

This is one of the most commonly used commands.

---

# Example Workflow

## Step 1 — Create File

Example:

```txt id="e9m4pq"
index.html
```

---

## Step 2 — Check Status

Run:

```bash id="d55fc3"
git status
```

You may see:

```txt id="f8q2vn"
Untracked files:
  index.html
```

---

## Step 3 — Add File

Run:

```bash id="ee2a8c"
git add index.html
```

---

## Step 4 — Check Status Again

Run:

```bash id="d17d75"
git status
```

Now you may see:

```txt id="j4m8qp"
Changes to be committed:
  index.html
```

This means the file is staged successfully.

---

# Real-World Understanding

Think of:

```bash id="7bc5b9"
git add
```

like:

> selecting files before uploading an assignment.

You decide what should be included.

---

# Why Developers Use git add

Developers use:

```bash id="da91c8"
git add
```

to:

* organize commits
* avoid unnecessary changes
* prepare clean project history
* manage workflow properly

---

# Common Beginner Mistakes

## Forgetting git add

Beginners sometimes:

* edit files
* directly try to commit

without staging changes first.

Git will not include unstaged files in commits.

---

## Using git add . Without Understanding

```bash id="eb3df2"
git add .
```

adds ALL files.

Be careful not to accidentally add:

* temporary files
* secret files
* unnecessary files

Always check status before committing.

---

# Helpful Command

After staging files, run:

```bash id="59c38f"
git status
```

to verify what is ready for commit.

---

# Beginner Tip

A good beginner workflow:

```txt id="y2m7vn"
Edit Files
   ↓
git status
   ↓
git add
   ↓
git status
   ↓
git commit
```

This helps you understand Git step by step.

---

# Simple Summary

```bash id="ba0dd8"
git add
```

helps developers:

* stage files
* prepare commits
* organize project changes

It moves files into the staging area before committing.

---

# Practice Task

✅ Create a file

Example:

```txt id="u5m8qp"
index.html
```

✅ Run:

```bash id="5fef8b"
git status
```

✅ Run:

```bash id="c8f0d6"
git add index.html
```

✅ Run:

```bash id="d0e5b1"
git status
```

✅ Observe the staged changes

---

# Next Step

Continue to:

```txt id="r7v2mk"
git-commit.md
```
