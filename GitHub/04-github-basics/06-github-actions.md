# GitHub Actions

GitHub Actions is GitHub's built-in automation tool.

In simple words:

> GitHub Actions helps developers automate repetitive tasks.

Instead of doing the same work manually every time, GitHub Actions can do it automatically.

---

# Why GitHub Actions Exists

Imagine every time you push code, you have to:

* run tests
* check code quality
* build the project
* deploy the application

Doing this manually every day would be tiring.

GitHub Actions automates these tasks.

---

# Real-World Example

Imagine your college assignment.

Every time you upload a file:

* spell checking runs automatically
* formatting is checked automatically
* plagiarism check runs automatically

You don't need to do anything manually.

GitHub Actions works similarly for software projects.

---

# What Can GitHub Actions Do?

GitHub Actions can:

* run tests automatically
* check code quality
* deploy websites
* send notifications
* build applications
* automate workflows

---

# Simple Workflow

```txt
Developer Pushes Code
          ↓
GitHub Action Starts
          ↓
Runs Tests
          ↓
Checks Code
          ↓
Reports Result
```

Everything happens automatically.

---

# What is a Workflow?

A workflow is a set of automated instructions.

Example:

```txt
When code is pushed
       ↓
Run tests
       ↓
Show result
```

This workflow can run without any manual effort.

---

# Where Are Workflows Stored?

GitHub Actions workflows are stored inside:

```txt
.github/
└── workflows/
```

Example:

```txt
.github/
└── workflows/
    └── test.yml
```

---

# What is a YAML File?

GitHub Actions uses:

```txt
.yml
```

files.

These files contain instructions for automation.

Example:

```yaml
name: Test Project

on: push

jobs:
  test:
    runs-on: ubuntu-latest
```

Don't worry if this looks confusing.

You will learn YAML later.

For now, just understand that workflows are written in YAML files.

---

# Common Uses of GitHub Actions

## Running Tests

Whenever code is pushed:

```txt
Push Code
    ↓
Run Tests Automatically
```

---

## Deploying Websites

Example:

```txt
Push Code
    ↓
Deploy Website Automatically
```

Many developers use GitHub Actions for deployment.

---

## Code Quality Checks

Actions can automatically:

* check formatting
* find errors
* enforce coding standards

---

# Why Companies Use GitHub Actions

Companies use GitHub Actions because it:

* saves time
* reduces manual work
* improves quality
* catches bugs early
* speeds up development

Automation is extremely important in modern software engineering.

---

# GitHub Actions and CI/CD

GitHub Actions is commonly used for:

```txt
CI/CD
```

---

## CI

Continuous Integration

Meaning:

> Automatically test code whenever changes are made.

---

## CD

Continuous Deployment

Meaning:

> Automatically deploy applications after successful tests.

---

# Real-World Example

Imagine a team working on a website.

Without GitHub Actions:

```txt
Push Code
    ↓
Run Tests Manually
    ↓
Deploy Manually
```

With GitHub Actions:

```txt
Push Code
    ↓
Tests Run Automatically
    ↓
Website Deploys Automatically
```

Much faster and safer.

---

# Common Beginner Mistakes

## Thinking GitHub Actions is Required Immediately

It is not.

Beginners should first learn:

* repositories
* commits
* branches
* pull requests

before learning automation.

---

## Being Scared by YAML Files

Many beginners feel overwhelmed when seeing workflow files.

That is normal.

Focus on understanding the concept first.

---

# Beginner Tip

At the beginner stage:

You only need to know:

> GitHub Actions = Automation

You do not need to memorize workflow syntax immediately.

---

# Why You Should Learn GitHub Actions Later

As you grow as a developer, GitHub Actions helps you:

* automate testing
* automate deployment
* improve productivity
* understand DevOps concepts

It becomes extremely valuable in professional development.

---

# Simple Summary

GitHub Actions is:

> GitHub's automation platform.

It helps developers:

* automate tasks
* run tests
* deploy projects
* improve workflows

GitHub Actions is widely used in startups, product companies, and open-source projects.

---

# Practice Task

✅ Open any popular GitHub repository

✅ Click the:

```txt
Actions
```

tab

✅ Observe existing workflows

✅ Try understanding what each workflow is doing

---

# Next Step

Continue to:

```txt
readme-files.md
```
