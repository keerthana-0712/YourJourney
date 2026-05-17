# How to Connect GitHub With Git

After installing Git and creating a GitHub account, the next step is connecting GitHub with Git on your computer.

This connection allows you to:

* push projects to GitHub
* pull repositories from GitHub
* collaborate with developers
* contribute to open source

Without connecting GitHub and Git, you cannot upload projects properly.

---

# Why Connection is Important

Git works mainly on your local computer.

GitHub works online.

Connecting them allows:

```txt id="u2q6fk"
Local Project ↔ GitHub Repository
```

This is one of the most important parts of the GitHub workflow.

---

# Two Common Authentication Methods

GitHub can connect with Git using:

* HTTPS
* SSH

For beginners:

> HTTPS is easier to start with.

You can learn SSH later.

---

# Step 1 — Create a Repository on GitHub

Go to:

[GitHub Official Website](https://github.com?utm_source=chatgpt.com)

After logging in:

* click **New Repository**
* enter repository name
* click **Create Repository**

Example repository name:

```txt id="x6k9tm"
my-first-project
```

---

# Step 2 — Copy Repository URL

After creating the repository, GitHub provides a URL.

Example:

```txt id="r4p2qy"
https://github.com/your-username/my-first-project.git
```

Copy this URL.

This connects your local project with GitHub.

---

# Step 3 — Open Local Project

Open your project folder in:

* VS Code
* terminal

Example folder:

```txt id="j7n4vz"
my-first-project
```

---

# Step 4 — Initialize Git

Run:

```bash id="8fc56d"
git init
```

This initializes Git in your project folder.

---

# Step 5 — Add Remote Repository

Run:

```bash id="54d2ea"
git remote add origin REPOSITORY_URL
```

Example:

```bash id="dbd4bc"
git remote add origin https://github.com/your-username/my-first-project.git
```

This command connects your local project to GitHub.

---

# What Does origin Mean?

```txt id="f1m8rx"
origin
```

is the default name for the remote GitHub repository.

Think of it as:

> the online version of your project.

---

# Step 6 — Verify Remote Connection

Run:

```bash id="a9d8c2"
git remote -v
```

You should see something like:

```txt id="y3v6kp"
origin  https://github.com/your-username/my-first-project.git
```

This means GitHub is connected successfully.

---

# Step 7 — Push Your Project

After adding files and commits, you can upload code using:

```bash id="0e7b44"
git push -u origin main
```

This pushes your local project to GitHub.

---

# What Happens After Push?

After pushing:

* your files appear on GitHub
* repository becomes online
* project can be shared publicly

Congratulations — your project is now on GitHub.

---

# Common Beginner Errors

## Error: Authentication Failed

Possible reasons:

* wrong credentials
* GitHub password issue
* outdated authentication method

GitHub may ask for:

* browser login
* personal access token

---

## Error: Repository Not Found

Possible reasons:

* wrong repository URL
* repository not created
* typing mistakes

Always double-check repository name and URL.

---

# Beginner Tip

Do not worry if pushing feels confusing initially.

GitHub workflows become easier with practice.

Every developer once struggled with:

* remotes
* pushes
* authentication
* terminal commands

---

# Real-World Understanding

Think of Git like:

> working on a project on your computer.

Think of GitHub like:

> uploading that project to the cloud for sharing and collaboration.

---

# Simple Summary

Connecting GitHub with Git allows developers to:

* upload projects
* collaborate online
* contribute to open source
* manage repositories professionally

This is the bridge between local development and online collaboration.

---

# Practice Task

✅ Create GitHub repository
✅ Copy repository URL
✅ Run:

```bash id="f4a0e2"
git remote add origin YOUR_REPOSITORY_URL
```

✅ Verify connection using:

```bash id="3dbd6f"
git remote -v
```

---

# Next Step

Continue to:

```txt id="p5q2kx"
03-git-basics/
```
