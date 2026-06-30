# Deleting Branches

After a branch has been successfully merged into another branch, it is usually no longer needed.

To keep your repository clean and organized, you can delete the branch.

Deleting old branches is a common practice in software development.

---

# 🎯 Learning Objectives

After completing this lesson, you will be able to:

- Understand why branches are deleted
- Delete local branches
- Delete remote branches
- Understand safe and force deletion
- Keep repositories organized

---

# 🤔 Why Delete Branches?

Imagine you created a branch:

```text
feature-login
```

You completed the feature.

You merged it into:

```text
main
```

Now the branch has served its purpose.

Keeping hundreds of old branches makes a repository difficult to manage.

Deleting completed branches keeps everything clean.

---

# 🌍 Real-World Example

Imagine building a house.

After construction is complete, you remove:

- temporary scaffolding
- ladders
- construction barriers

The house remains.

Similarly, after a feature is merged, the temporary branch can be removed.

---

# 🖼️ Visual Representation

Before deletion:

```text
main
│
├── feature-login
├── feature-dashboard
└── feature-profile
```

After deleting the merged branch:

```text
main
│
├── feature-dashboard
└── feature-profile
```

The project remains exactly the same.

Only the unused branch disappears.

---

# Delete a Local Branch

To delete a local branch:

```bash
git branch -d feature-login
```

Git deletes the branch **only if it has already been merged**.

This is the safest option.

---

# Command Breakdown

```bash
git branch -d feature-login
```

| Part | Meaning |
|------|---------|
| git | Git command |
| branch | Manage branches |
| -d | Delete a merged branch |
| feature-login | Branch name |

---

# Force Delete a Branch

Sometimes Git refuses to delete a branch because it contains unmerged work.

If you are absolutely sure you don't need those changes, use:

```bash
git branch -D feature-login
```

Notice the capital **D**.

⚠️ This permanently deletes the branch, even if its work hasn't been merged.

Use it carefully.

---

# Delete a Remote Branch

If the branch exists on GitHub, delete it using:

```bash
git push origin --delete feature-login
```

This removes the branch from the remote repository.

---

# List Available Branches

Before deleting, check your branches:

```bash
git branch
```

Example:

```text
* main
feature-login
feature-profile
```

The `*` shows your current branch.

---

# Important Rule

You **cannot delete the branch you're currently using**.

Example:

```text
* feature-login
```

Trying to delete it will result in an error.

First switch to another branch:

```bash
git switch main
```

Then delete:

```bash
git branch -d feature-login
```

---

# Safe Workflow

```text
Create Branch
       ↓
Develop Feature
       ↓
Commit Changes
       ↓
Merge Branch
       ↓
Switch to Main
       ↓
Delete Branch
```

This is the workflow followed in most projects.

---

# Local vs Remote Deletion

| Local Branch | Remote Branch |
|--------------|---------------|
| Exists on your computer | Exists on GitHub |
| `git branch -d` | `git push origin --delete` |

Deleting a local branch does **not** delete the remote branch.

Deleting the remote branch does **not** automatically delete local branches.

---

# Common Beginner Mistakes

## ❌ Deleting Before Merging

Always verify that your branch has been merged.

Deleting an unmerged branch may result in lost work.

---

## ❌ Using `-D` Unnecessarily

Use:

```bash
git branch -d
```

whenever possible.

Reserve:

```bash
git branch -D
```

for special situations.

---

## ❌ Trying to Delete the Current Branch

Switch to another branch first.

Git will not allow you to delete the branch you're currently using.

---

# 💼 Industry Insight

Many companies automatically delete feature branches after a Pull Request is merged.

This keeps repositories clean and makes it easier to identify active work.

Some repositories even enable **automatic branch deletion** after every successful merge.

---

# 💡 Pro Tip

Delete feature branches once:

- the Pull Request is merged
- the code is deployed
- no further work is needed

Clean repositories are easier to maintain.

---

# 📝 Quick Quiz

### 1. Which command safely deletes a merged local branch?

- A. `git branch -D`
- B. `git delete`
- C. `git branch -d`
- D. `git remove`

<details>
<summary>✅ Answer</summary>

**C. `git branch -d`**

</details>

---

### 2. Which command deletes a remote branch?

- A. `git branch -r`
- B. `git push origin --delete feature-login`
- C. `git remote delete`
- D. `git delete origin`

<details>
<summary>✅ Answer</summary>

**B**

</details>

---

# 💻 Practice Exercise

1. Create a branch:

```bash
git switch -c feature-contact
```

2. Merge it into `main`.

3. Switch back to `main`.

4. Delete the branch:

```bash
git branch -d feature-contact
```

5. Verify:

```bash
git branch
```

The branch should no longer appear.

---

# 🏆 Challenge

Create three branches:

```text
feature-home

feature-about

feature-contact
```

Merge each one into `main`.

Delete all three branches.

Finally, verify that only the branches you still need remain.

---

# 📚 Summary

Today you learned:

- ✅ Why branches are deleted
- ✅ How to delete local branches
- ✅ How to delete remote branches
- ✅ Difference between `-d` and `-D`
- ✅ Safe branch cleanup workflow

Deleting completed branches is a simple habit that keeps repositories clean and professional.

---

# 🚀 Next Lesson

Continue to:

```text
branching-best-practices.md
```
