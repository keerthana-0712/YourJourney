# Merge Conflicts

Sooner or later, every developer encounters a **merge conflict**.

Don't worry—it's completely normal.

Even experienced developers deal with merge conflicts regularly.

A merge conflict simply means:

> Git doesn't know which changes to keep because the same part of a file was modified in different branches.

Git asks **you** to decide.

---

# 🎯 Learning Objectives

After completing this lesson, you will be able to:

- Understand what a merge conflict is
- Learn why merge conflicts happen
- Resolve merge conflicts
- Prevent unnecessary conflicts

---

# 🤔 Why Do Merge Conflicts Happen?

Imagine two developers working on the same file.

Developer A changes:

```text
Welcome to our website!
```

Developer B changes the same line to:

```text
Hello and welcome!
```

Now Git has a question:

> Which version should I keep?

Git cannot guess.

Instead, it creates a merge conflict.

---

# 🌍 Real-World Example

Imagine two friends editing the same paragraph in a Word document.

Friend A writes:

```
The meeting starts at 9 AM.
```

Friend B writes:

```
The meeting starts at 10 AM.
```

When combining both versions, the computer cannot know which sentence is correct.

Someone must decide manually.

Git works the same way.

---

# 🖼️ Visual Representation

```mermaid
gitGraph
    commit id: "Start"

    branch feature-login

    checkout feature-login

    commit id: "Edit README"

    checkout main

    commit id: "Edit README"

    merge feature-login
```

Both branches modified the same file before merging.

---

# Example Scenario

Initial file:

```text
Hello World
```

---

## Main Branch

Changes to:

```text
Welcome to GitHub
```

---

## Feature Branch

Changes to:

```text
Welcome to Open Source
```

Now Git doesn't know which version should be kept.

---

# What Does a Merge Conflict Look Like?

Git marks the conflicting section like this:

```text
<<<<<<< HEAD
Welcome to GitHub
=======
Welcome to Open Source
>>>>>>> feature-login
```

Let's understand this.

---

# Conflict Markers

## `<<<<<<< HEAD`

This is the version currently in your branch.

---

## `=======`

Separator between the two versions.

---

## `>>>>>>> feature-login`

This is the version coming from the branch being merged.

---

# Resolving a Merge Conflict

Step 1:

Open the file.

You'll see conflict markers.

---

Step 2:

Decide which version to keep.

Example:

```text
Welcome to GitHub and Open Source
```

---

Step 3:

Delete the conflict markers.

Your file should now look clean.

---

Step 4:

Save the file.

---

Step 5:

Stage the resolved file.

```bash
git add README.md
```

---

Step 6:

Complete the merge.

```bash
git commit
```

Git creates a merge commit.

Conflict resolved.

---

# Visual Workflow

```text
Conflict
     ↓
Open File
     ↓
Choose Correct Version
     ↓
Delete Conflict Markers
     ↓
Save File
     ↓
git add
     ↓
git commit
```

---

# Why Merge Conflicts Are Not Bad

Many beginners think:

> "I broke Git!"

No.

Merge conflicts simply mean:

Two different changes need your decision.

They're a normal part of software development.

---

# How to Reduce Merge Conflicts

## ✅ Pull Regularly

Run:

```bash
git pull
```

before starting work.

---

## ✅ Keep Branches Small

Instead of one huge feature:

```
feature-everything
```

Create smaller branches:

```
feature-login

feature-profile

feature-payment
```

---

## ✅ Communicate With Your Team

If multiple people are editing the same file, coordinate with each other.

---

## ✅ Merge Frequently

Don't keep branches open for weeks.

Merge completed work regularly.

---

# Common Beginner Mistakes

## ❌ Deleting Everything

Some beginners delete the entire file during a conflict.

Instead:

Read carefully.

Choose the correct changes.

---

## ❌ Keeping Conflict Markers

Never commit files containing:

```text
<<<<<<<
=======
>>>>>>>
```

These markers should always be removed after resolving the conflict.

---

## ❌ Panicking

Merge conflicts are completely normal.

Every professional developer encounters them.

---

# 💼 Industry Insight

In large software companies:

Merge conflicts happen every day.

Teams resolve them through:

- code reviews
- communication
- testing
- pair programming

The goal is not to avoid every conflict but to resolve them correctly.

---

# 💡 Pro Tip

The best way to prevent merge conflicts is:

- pull often
- commit regularly
- keep branches focused on one task
- merge small changes frequently

Small branches = fewer conflicts.

---

# 📝 Quick Quiz

### 1. Why does a merge conflict occur?

- A. Git is broken
- B. Internet connection failed
- C. Git cannot automatically combine conflicting changes
- D. Repository is deleted

<details>
<summary>✅ Answer</summary>

**C**

Git needs you to decide which changes to keep.

</details>

---

### 2. Which symbols indicate a merge conflict?

- A. `***`
- B. `<<< >>>`
- C. `<<<<<<<`, `=======`, `>>>>>>>`
- D. `+++`

<details>
<summary>✅ Answer</summary>

**C**

These are Git's conflict markers.

</details>

---

# 💻 Practice Exercise

Create two branches.

In both branches:

Modify the same line inside:

```
README.md
```

Try merging them.

Observe:

- conflict markers
- Git's message
- resolution process

Then resolve the conflict manually.

---

# 🏆 Challenge

Create:

```
feature-about

feature-contact
```

Modify the same heading in both branches.

Merge them.

Resolve the conflict without deleting any useful content.

---

# 📚 Summary

Today you learned:

- ✅ What a merge conflict is
- ✅ Why merge conflicts happen
- ✅ How to resolve conflicts
- ✅ How to reduce conflicts
- ✅ Why merge conflicts are completely normal

Understanding merge conflicts is a major milestone in learning Git.

---

# 🚀 Next Lesson

Continue to:

```text
deleting-branches.md
```
