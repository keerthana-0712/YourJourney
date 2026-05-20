# git diff

The command:

```bash id="1b8e63"
git diff
```

is used to view changes made in files before committing them.

In simple words:

> git diff shows what was changed in your code.

Developers use it to:

* review changes
* compare file versions
* find mistakes
* understand modifications before committing

---

# Why git diff is Important

Before creating commits, developers often check:

```bash id="63f6cd"
git diff
```

to verify:

* what changed
* whether changes are correct
* if anything was accidentally modified

This helps avoid mistakes in commits.

---

# Basic Syntax

```bash id="0f6bc0"
git diff
```

Run this command inside your Git repository.

---

# What Does git diff Compare?

By default:

```bash id="ebed74"
git diff
```

compares:

> current file changes vs last committed version.

It shows:

* added lines
* removed lines
* modified content

---

# Example Workflow

---

## Step 1 — Create File

Example:

```txt id="g5m8qp"
index.html
```

---

## Step 2 — Commit File

```bash id="5a6d25"
git add .
git commit -m "Initial commit"
```

---

## Step 3 — Modify File

Add new content inside:

```txt id="k7v2qm"
index.html
```

---

## Step 4 — Run git diff

```bash id="46f95c"
git diff
```

Git now shows the differences between:

* previous version
* current changes

---

# Example Output

Example:

```txt id="d4m8vq"
+ Added new heading
- Removed old paragraph
```

---

# Understanding Symbols

| Symbol | Meaning      |
| ------ | ------------ |
| `+`    | Added line   |
| `-`    | Removed line |

These symbols help developers understand changes quickly.

---

# Real-World Understanding

Think of:

```bash id="e0c11c"
git diff
```

like:

> comparing “before” and “after” versions of your assignment.

It highlights exactly what changed.

---

# Why Developers Use git diff

Developers use:

```bash id="fb8b37"
git diff
```

to:

* review code changes
* catch mistakes
* verify edits
* debug issues
* prepare cleaner commits

It is extremely useful in professional development.

---

# Useful Variations

---

## Compare Staged Changes

```bash id="3cb47b"
git diff --staged
```

Shows:

> staged changes waiting for commit.

---

## Compare Specific File

```bash id="ec5bfe"
git diff index.html
```

Shows changes only for:

```txt id="n6q4vp"
index.html
```

---

# Common Beginner Mistakes

## Forgetting to Check Changes

Beginners sometimes:

* make accidental edits
* commit wrong files
* miss important modifications

Using:

```bash id="75caa9"
git diff
```

helps prevent these mistakes.

---

## Confusion About Colored Output

Git may display:

* green lines
* red lines

Usually:

* green = added
* red = removed

This is normal behavior.

---

# Helpful Beginner Workflow

Good workflow:

```txt id="j5m8qp"
Edit Files
    ↓
git diff
    ↓
git add
    ↓
git commit
```

This helps verify changes before saving them permanently.

---

# Real Team Usage

In companies, developers use:

```bash id="e8e1d6"
git diff
```

to:

* review features
* inspect bug fixes
* compare changes during code reviews
* debug problems

It is part of daily development workflow.

---

# Beginner Tip

Use:

```bash id="f587b4"
git diff
```

frequently while learning Git.

It improves understanding of:

* file tracking
* version control
* project history

---

# Simple Summary

```bash id="ea848f"
git diff
```

helps developers:

* compare file changes
* review modifications
* detect mistakes
* understand project updates

It shows differences between file versions.

---

# Practice Task

✅ Create or modify a file

✅ Run:

```bash id="a7554c"
git diff
```

✅ Observe:

* added lines
* removed lines
* modified content

---

# Next Step

Continue to:

```txt id="x3q8pm"
04-github-basics/
```
