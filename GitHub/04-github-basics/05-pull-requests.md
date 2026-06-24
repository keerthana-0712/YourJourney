# Pull Requests (PRs)

A **Pull Request** (often called a **PR**) is one of the most important concepts in GitHub and Open Source.

In simple words:

> A Pull Request is a request to merge your changes into another repository or branch.

It allows developers to:

* suggest changes
* review code
* discuss improvements
* merge contributions safely

---

# Why Pull Requests Exist

Imagine a project used by thousands of people.

If everyone could directly modify the code:

* bugs could be introduced
* code quality could decrease
* project stability could suffer

Instead, developers first submit their changes through a Pull Request.

This allows project maintainers to review changes before accepting them.

---

# Real-World Example

Imagine your teacher gives a class project.

You make some improvements and want them included in the final project.

Instead of directly editing the final submission, you say:

> "I made these changes. Please review them and include them if they are correct."

That request is similar to a Pull Request.

---

# How Pull Requests Work

Basic workflow:

```txt
Original Repository
        ↓
Fork Repository
        ↓
Clone Repository
        ↓
Make Changes
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

This is the standard workflow used in open-source projects.

---

# What Happens Inside a Pull Request?

A Pull Request shows:

* changed files
* added code
* removed code
* commit history
* discussion comments

Maintainers can review everything before accepting changes.

---

# Creating a Pull Request

## Step 1

Fork a repository.

---

## Step 2

Clone the repository.

---

## Step 3

Make changes.

Example:

```txt
Fix typo in README
```

---

## Step 4

Commit changes.

```bash
git add .
git commit -m "Fixed README typo"
```

---

## Step 5

Push changes.

```bash
git push origin main
```

---

## Step 6

Go to GitHub.

GitHub may show:

```txt
Compare & Pull Request
```

Click it.

---

## Step 7

Add:

### Title

Example:

```txt
Fix typo in README documentation
```

### Description

Example:

```txt
Corrected spelling mistakes in installation section.
```

---

## Step 8

Click:

```txt
Create Pull Request
```

Done.

---

# Anatomy of a Pull Request

A good Pull Request contains:

## Title

Short summary.

Example:

```txt
Add installation guide for Windows users
```

---

## Description

Detailed explanation.

Example:

```txt
Added Windows installation instructions for beginners.
```

---

## Linked Issue (Optional)

Example:

```txt
Fixes #42
```

This automatically closes Issue #42 when merged.

---

# Why Pull Requests Are Important

Pull Requests help teams:

* review code
* prevent mistakes
* discuss improvements
* maintain quality
* collaborate safely

Almost every professional software team uses Pull Requests.

---

# Code Review Process

Before merging, maintainers often review:

### Code Quality

Is the code clean?

### Functionality

Does it work correctly?

### Documentation

Is everything properly explained?

### Project Standards

Does it follow project rules?

---

# Pull Request Status

A Pull Request can be:

| Status            | Meaning               |
| ----------------- | --------------------- |
| Open              | Waiting for review    |
| Approved          | Ready to merge        |
| Changes Requested | Improvements needed   |
| Merged            | Successfully accepted |
| Closed            | Not accepted          |

---

# Pull Requests in Open Source

Most open-source contributions happen through Pull Requests.

Examples:

* fixing bugs
* updating documentation
* improving UI
* adding features
* correcting spelling mistakes

Even small contributions often use Pull Requests.

---

# Common Beginner Mistakes

## Huge Pull Requests

Beginners sometimes modify many unrelated files.

Instead:

✅ Keep Pull Requests small.

---

## Poor Descriptions

Bad:

```txt
Updated files
```

Good:

```txt
Added beginner-friendly installation instructions.
```

---

## Not Following Contribution Guidelines

Many repositories provide:

```txt
CONTRIBUTING.md
```

Always read it before contributing.

---

# Beginner Tip

Your first Pull Request does not need to be a major feature.

Start with:

* documentation fixes
* typo corrections
* README improvements
* small bug fixes

These are excellent first contributions.

---

# Real Open Source Workflow

```txt
Issue Created
      ↓
Contributor Works
      ↓
Commit Changes
      ↓
Push Changes
      ↓
Create Pull Request
      ↓
Maintainer Reviews
      ↓
Merge Pull Request
      ↓
Issue Closed
```

This workflow powers thousands of open-source projects.

---

# Simple Summary

A Pull Request is:

> A request to merge your changes into a project.

Pull Requests help developers:

* contribute safely
* review code
* collaborate professionally
* improve project quality

They are one of the most important concepts in GitHub and Open Source.

---

# Practice Task

✅ Fork a repository

✅ Make a small change

✅ Commit the change

✅ Push it to GitHub

✅ Create your first Pull Request

---

# Next Step

Continue to:

```txt
github-actions.md
```
