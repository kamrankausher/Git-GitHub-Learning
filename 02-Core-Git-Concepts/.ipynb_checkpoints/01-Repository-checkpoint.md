# Repository

## What Is a Repository?
A repository (repo) is a **folder that Git is tracking**.

In simple words:
> A repository is a project with version history.

---

## Types of Repositories

### 1. Local Repository
- Exists on your computer
- Created using `git init`
- Stores complete history locally

### 2. Remote Repository
- Exists on GitHub
- Used for sharing and backup
- Connected using `git remote`

---

## How a Repository Is Created
When you run:
```bash
git init

Git:

Creates a .git folder

Starts tracking changes

Initializes version history

Why .git Folder Is Important

The .git folder contains:

Commit history

Branch information

Configuration

Metadata

⚠️ Deleting .git removes Git history.

Summary

A repository is the core unit of Git that stores project history.


---

## 📄 File 2  
### `02-Working-Directory.md`

```md
# Working Directory

## What Is Working Directory?
The working directory is your **normal project folder** where you:
- Create files
- Edit files
- Delete files

---

## Role of Working Directory
- Contains actual files
- Changes are not tracked automatically
- Git monitors changes but does not save them yet

---

## Example
Editing a file:
```bash
notes.md

This change exists only in the working directory until staged.

Summary

The working directory is where you actively work on files.


---

## 📄 File 3  
### `03-Staging-Area.md`

```md
# Staging Area

## What Is Staging Area?
The staging area is a **temporary holding area** for changes before committing.

In simple words:
> It tells Git which changes you want to save.

---

## Why Staging Area Exists
- Select specific changes
- Avoid committing unwanted edits
- Create clean commits

---

## How to Add to Staging
```bash
git add filename

Add all changes:
git add .

Staging vs Working Directory

Working Directory → raw changes

Staging Area → selected changes

Summary

Staging gives you control over what goes into a commit.


---

## 📄 File 4  
### `04-Commits.md`

```md
# Commits

## What Is a Commit?
A commit is a **snapshot of your project** at a specific time.

Each commit:
- Has a unique ID (hash)
- Stores changes permanently
- Includes author and message

---

## Why Commits Matter
- Save progress
- Enable rollback
- Show project history

---

## How to Create a Commit
```bash
git commit -m "Meaningful message"

Good Commit Message Rules

Short and clear

Describes what changed

Avoid vague messages like "update"

Example:
git commit -m "Add Git basics notes"

Summary

Commits are permanent save points in Git history.


---

# 🧠 CORE CONCEPT YOU MUST REMEMBER

Working Directory → Staging Area → Repository


This is **the heart of Git**.

---

# ✅ WHAT TO DO NOW

1. Create all 4 files inside `02-Core-Git-Concepts/`
2. Paste notes
3. Run:

```bash
git add .
git commit -m "Add core Git concepts notes"
git push

