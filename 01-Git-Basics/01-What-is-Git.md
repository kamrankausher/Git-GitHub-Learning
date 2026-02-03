# What is Git?

## Definition
Git is a **distributed version control system** used to track changes in files and coordinate work between multiple people.

In simple words:
> Git remembers every change you make to your project and allows you to go back in time safely.

---

## What Git Is NOT
- Git is NOT GitHub
- Git is NOT only for programmers
- Git is NOT an online tool

Git runs **locally on your computer**.

---

## Why Git Is Needed
Git helps you to:
- Track file changes
- Recover deleted or broken code
- Experiment without fear
- Collaborate with others
- Maintain clean project history

---

## How Git Works (High-Level)
Git works by creating **snapshots** of your project instead of saving full copies.

Each snapshot:
- Has a unique ID
- Stores only changes
- Is permanent and secure

---

## Where Git Lives
Git lives:
- Inside your project folder
- In a hidden `.git` directory

When you run:
```bash
git init
Git creates .git and starts tracking the project.

When You Should Use Git

Use Git when:

You start any project

You write notes or documentation

You work with a team

You want backup + history

Key Benefits of Git

Fast

Offline support

Secure history

Powerful branching

Industry standard

Summary

Git is the backbone of modern development and the foundation for collaboration tools like GitHub.


---

# 📘 Chapter 2 — File 2  
## `01-Git-Basics/02-Git-Installation.md`

```md
# Git Installation

## Why Installation Is Required
Git must be installed on your computer to:
- Track files
- Create commits
- Push code to GitHub

Without Git installed, GitHub cannot be used properly.

---

## Installing Git on Windows

### Step 1
Download Git from the official website.

### Step 2
Run the installer.

### Step 3 (IMPORTANT OPTIONS)
- Select **Git Bash**
- Keep default settings
- Choose **"Git from the command line and also from 3rd-party software"**

---

## Verify Installation
Open Git Bash or VS Code terminal and run:
```bash
git --version
If a version appears → Git installed successfully.

Summary

Git installation is a one-time setup required before using Git commands.

---

# 📘 Chapter 2 — File 3  
## `01-Git-Basics/03-Git-Configuration.md`

```md
# Git Configuration

## Why Configuration Is Needed
Git needs to know:
- Who you are
- Which email to attach to commits

This information appears in project history.

---

## Setting Username
```bash
git config --global user.name "Your Name"

Setting Email
git config --global user.email "your-email@example.com"

Check Configuration
git config --list

Local vs Global Config
  -Global: applies to all projects
  -Local: applies to one project

  Summary

Configuration connects your identity with Git commits.

---

# 📘 Chapter 2 — File 4  
## `01-Git-Basics/04-Git-Workflow.md`

> This is **CRITICAL**.  
> This explains **WHEN and HOW to push to GitHub**.

```md
# Git Workflow

## What Is Git Workflow?
Git workflow is the **step-by-step process** of saving and sharing your work.

---

## The 4 Main Stages

1. Working Directory  
2. Staging Area  
3. Local Repository  
4. Remote Repository (GitHub)

---

## Step-by-Step Workflow

### Step 1: Edit Files
You create or modify files.

### Step 2: Check Status
```bash
git status

Step 3: Add Changes
git add .

Step 4: Commit Changes
git commit -m "Describe what you changed"

Step 5: Push to GitHub
git push

WHEN to Push to GitHub

Push when:

A logical change is complete

Notes or features are stable

You want online backup

DO NOT push:

Broken code

Half-written notes

Summary

The correct order is:

Edit → Add → Commit → Push

Never change this order.


---

# ✅ WHAT YOU MUST DO NOW

1. Create all 4 files inside `01-Git-Basics/`
2. Paste notes exactly
3. Run:

```bash
git add .
git commit -m "Add Git basics notes"
git push
