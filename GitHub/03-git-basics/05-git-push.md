# git push

The command:

```bash id="e1b8c4"
git push
```

is used to upload your local project changes to GitHub.

In simple words:

> git push sends your commits from your computer to GitHub.

This allows your project to become available online.

---

# Why git push is Important

Without:

```bash id="d8f72a"
git push
```

your commits stay only on your local computer.

Pushing changes helps developers:

* upload projects online
* back up work
* collaborate with teams
* contribute to open source
* update repositories on GitHub

---

# Basic Workflow

Basic Git workflow:

```txt id="f4m9qp"
Write Code
    ↓
git add
    ↓
git commit
    ↓
git push
```

After committing changes, developers push them to GitHub.

---

# Basic Syntax

```bash id="9fa64f"
git push origin main
```

---

# Understanding the Command

## git push

Uploads commits to GitHub.

---

## origin

Name of the remote repository.

Usually refers to:

> your GitHub repository.

---

## main

Branch name being pushed.

Most modern repositories use:

```txt id="w6q2vn"
main
```

as the default branch.

---

# First Push Command

Sometimes beginners use:

```bash id="f1cfaa"
git push -u origin main
```

---

# What Does -u Mean?

```txt id="x2m8vp"
-u
```

means:

> remember this remote branch connection for future pushes.

After using `-u` once, future pushes become simpler.

Example:

```bash id="5f12a9"
git push
```

---

# Example Workflow

## Step 1 — Add Files

```bash id="4ff17f"
git add .
```

---

## Step 2 — Commit Changes

```bash id="6530d8"
git commit -m "Added homepage"
```

---

## Step 3 — Push to GitHub

```bash id="f68dbd"
git push origin main
```

Your project is now uploaded to GitHub.

---

# What Happens After Push?

After pushing:

* commits appear on GitHub
* files become visible online
* repository gets updated

You can refresh your GitHub repository page to see changes.

---

# Real-World Understanding

Think of:

```bash id="f6c2f1"
git push
```

like:

> uploading your latest project work to the cloud.

Your local project becomes available online.

---

# Common Beginner Errors

## Authentication Error

GitHub may ask for:

* browser authentication
* personal access token

This is normal security behavior.

---

## Repository Not Connected

If GitHub is not connected properly, Git may show errors.

Always verify remote repository setup using:

```bash id="48c9bc"
git remote -v
```

---

## No Commits to Push

Beginners sometimes try:

```bash id="0c5d8a"
git push
```

before creating commits.

Git only pushes committed changes.

---

# Helpful Commands

Check remote repository:

```bash id="f4de74"
git remote -v
```

Check status before pushing:

```bash id="12f95e"
git status
```

---

# Beginner Tip

Good beginner workflow:

```txt id="t7m4vq"
git status
    ↓
git add .
    ↓
git commit
    ↓
git push
```

Following the same workflow regularly helps build confidence.

---

# Why Developers Push Frequently

Developers push changes regularly to:

* save progress online
* collaborate safely
* avoid losing work
* keep repositories updated

Frequent pushes are a good development habit.

---

# Simple Summary

```bash id="db0f49"
git push
```

helps developers:

* upload commits to GitHub
* share projects online
* collaborate with teams
* back up project history

It connects local development with GitHub repositories.

---

# Practice Task

✅ Create or edit a file

✅ Run:

```bash id="24295d"
git add .
```

✅ Run:

```bash id="cd5fc0"
git commit -m "Updated project"
```

✅ Run:

```bash id="27a20f"
git push origin main
```

✅ Refresh GitHub repository page

---

# Next Step

Continue to:

```txt id="w3q8pn"
git-pull.md
```
