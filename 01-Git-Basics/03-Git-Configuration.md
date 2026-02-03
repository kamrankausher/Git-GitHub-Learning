
# Git Configuration

## Why Configuration Is Needed
Git needs to know:
- Who you are
- Which email to attach to commits

This information appears in project history.

---

## Setting Username

git config --global user.name "Your Name"

### Setting Email
git config --global user.email "your-email@example.com"

### Check Configuration
git config --list

#### Local vs Global Config

-Global: applies to all projects

-Local: applies to one project

## Summary

Configuration connects your identity with Git commits.