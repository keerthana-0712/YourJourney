# GitHub Workflow

A GitHub workflow is the step-by-step process developers follow while working on projects.

In simple words:

> A GitHub workflow is the journey of code from your computer to a GitHub repository.

Understanding the workflow is more important than memorizing commands because this is how real developers work every day.

---

# Why GitHub Workflow Matters

GitHub is not just a place to upload code.

It helps developers:

* collaborate with teams
* manage projects
* review code
* contribute to open source
* build software professionally

Understanding the workflow helps you become industry-ready.

---

# The Basic GitHub Workflow

Most projects follow this workflow:

```txt
Create Repository
        ↓
Clone Repository
        ↓
Make Changes
        ↓
Check Status
        ↓
Add Changes
        ↓
Commit Changes
        ↓
Push Changes
        ↓
Create Pull Request
        ↓
Review
        ↓
Merge
```

This is one of the most common workflows used in software development.

---

# Step 1 — Create a Repository

Every project starts with a repository.

A repository stores:

* code
* documentation
* project history
* issues
* pull requests

Example:

```txt
expense-tracker
portfolio-website
weather-app
```

---

# Step 2 — Clone Repository

Developers download the repository to their local computer.

Command:

```bash
git clone REPOSITORY_URL
```

Now they can work on the project locally.

---

# Step 3 — Make Changes

Developers:

* write code
* fix bugs
* update documentation
* add new features

Example:

```txt
Added login page
Fixed navbar bug
Updated README
```

---

# Step 4 — Check Project Status

Before saving changes:

```bash
git status
```

This helps developers see:

* changed files
* staged files
* untracked files

---

# Step 5 — Add Changes

Stage files for commit.

```bash
git add .
```

or

```bash
git add filename
```

---

# Step 6 — Commit Changes

Save changes into Git history.

```bash
git commit -m "Added login page"
```

A commit acts like a project checkpoint.

---

# Step 7 — Push Changes

Upload commits to GitHub.

```bash
git push origin main
```

Now the repository online contains the latest changes.

---

# Step 8 — Create Pull Request

In team projects and open source:

Developers usually don't modify the main project directly.

Instead they:

* push changes
* create a Pull Request
* request review

Example:

```txt
Added beginner installation guide
```

---

# Step 9 — Review Process

Project maintainers review:

* code quality
* functionality
* documentation
* project standards

They may:

* approve changes
* request modifications
* ask questions

---

# Step 10 — Merge Changes

After approval:

The Pull Request is merged.

The changes become part of the project.

---

# Real Open Source Workflow

A typical open-source contribution looks like:

```txt
Find Issue
     ↓
Fork Repository
     ↓
Clone Fork
     ↓
Make Changes
     ↓
Commit
     ↓
Push
     ↓
Create Pull Request
     ↓
Review
     ↓
Merge
```

This workflow is used by thousands of open-source projects.

---

# Real Company Workflow

A company workflow is usually:

```txt
Create Branch
      ↓
Develop Feature
      ↓
Commit Changes
      ↓
Push Branch
      ↓
Create Pull Request
      ↓
Code Review
      ↓
Merge
```

This helps teams work safely without affecting the main project.

---

# Why GitHub Workflow is Important

Learning workflow helps developers:

* collaborate effectively
* understand teamwork
* contribute to open source
* prepare for internships
* prepare for placements

Companies care about workflow knowledge, not just coding skills.

---

# Common Beginner Mistakes

## Skipping Commits

Beginners often make huge changes before committing.

Better approach:

```txt
Small Change
    ↓
Commit
```

Make commits regularly.

---

## Directly Editing Main Branch

In professional projects:

Developers usually create branches first.

---

## Not Reading Pull Request Feedback

Code reviews are learning opportunities.

Always read and understand feedback.

---

# Beginner Tip

Don't try to memorize the entire workflow immediately.

Practice it repeatedly:

```txt
Clone
 ↓
Edit
 ↓
Add
 ↓
Commit
 ↓
Push
```

Soon it becomes natural.

---

# Complete Workflow Summary

```txt
Repository
    ↓
Clone
    ↓
Code
    ↓
Status
    ↓
Add
    ↓
Commit
    ↓
Push
    ↓
Pull Request
    ↓
Review
    ↓
Merge
```

This is the foundation of GitHub collaboration.

---

# Simple Summary

A GitHub workflow is:

> The process developers use to build, manage, review, and share code.

Understanding the workflow helps you:

* work professionally
* contribute to open source
* collaborate with teams
* become a better developer

---

# Practice Task

✅ Create a repository

✅ Clone it locally

✅ Add a file

✅ Commit changes

✅ Push to GitHub

✅ Observe the complete workflow

---

# Section Completed 🎉

You have now completed:

```txt
04 - GitHub Basics
```

Next, you can move to:

```txt
05 - Branching
```

This is where you start learning how professional developers work on features without breaking the main project. 🚀
