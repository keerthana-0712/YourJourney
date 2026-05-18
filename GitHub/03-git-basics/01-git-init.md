# git init

The command:

```bash id="79e41d"
git init
```

is one of the first and most important Git commands.

It is used to:

> initialize Git inside a project folder.

This command converts a normal folder into a Git repository.

---

# What Does git init Mean?

## git

Git version control system

## init

Short form of:

> initialize

So:

```bash id="6e0bc2"
git init
```

means:

> start Git tracking in this folder.

---

# Why git init is Important

Before Git can track changes, Git must first understand:

* which folder is the project
* where project history should be stored

`git init` creates this setup.

Without running:

```bash id="9c5d17"
git init
```

Git commands like:

* commit
* add
* status

will not work properly inside the folder.

---

# Real-World Understanding

Imagine creating a new notebook for a subject.

Before writing notes, you first:

* create notebook
* organize pages
* prepare structure

Similarly:

```bash id="e8e0cf"
git init
```

prepares your project for version control.

---

# How to Use git init

## Step 1 — Open Project Folder

Create or open a folder.

Example:

```txt id="s8m2qv"
my-project
```

---

## Step 2 — Open Terminal

Open terminal inside the folder.

In VS Code:

```txt id="2m7xqn"
Terminal → New Terminal
```

---

## Step 3 — Run Command

Run:

```bash id="f767dc"
git init
```

---

# Example Output

You may see:

```txt id="u4n8pd"
Initialized empty Git repository
```

This means Git is now active inside your project.

---

# What Happens Internally?

After running:

```bash id="f8f9c2"
git init
```

Git creates a hidden folder called:

```txt id="e5v1rq"
.git
```

This folder stores:

* commits
* branches
* project history
* Git configuration

Important:
Never delete the `.git` folder unless you want to remove Git tracking completely.

---

# How to Check If Git is Initialized

Run:

```bash id="12b659"
git status
```

If Git is initialized successfully, Git will show project status information.

Example:

```txt id="d7q9km"
On branch main

No commits yet
```

---

# Common Beginner Mistakes

## Running git init in Wrong Folder

Always make sure terminal is opened inside the correct project folder.

---

## Initializing Multiple Times

Running:

```bash id="0d71f4"
git init
```

again usually does not cause major problems, but beginners should avoid unnecessary reinitialization.

---

# Beginner Tip

Think of:

```bash id="4a7d19"
git init
```

as:

> “Turning ON Git tracking for your project.”

This simple understanding helps beginners remember its purpose easily.

---

# Real Workflow Example

Basic project workflow:

```txt id="k8p4vz"
Create Folder
      ↓
Run git init
      ↓
Add Files
      ↓
Commit Changes
      ↓
Push to GitHub
```

`git init` is usually the first Git command in a new project.

---

# Simple Summary

```bash id="d9e80f"
git init
```

helps developers:

* initialize repositories
* start version control
* prepare projects for Git tracking

It converts a normal folder into a Git repository.

---

# Practice Task

✅ Create a folder named:

```txt id="7m2vqa"
my-first-project
```

✅ Open terminal inside the folder

✅ Run:

```bash id="84832d"
git init
```

✅ Run:

```bash id="74b02f"
git status
```

---

# Next Step

Continue to:

```txt id="h5q9vn"
git-status.md
```
