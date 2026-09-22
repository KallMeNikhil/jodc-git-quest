# JODC Git Quest 🧭

Welcome to **Git Quest: Your First Contribution** — a hands-on workshop by **JODC**.

By the end of this session, your work will be inside this real shared repository, reviewed by a peer, and you will have survived a merge conflict.

## What this quest is

This repository is deliberately tiny. There's no app, no code to build — **the Git workflow itself is the project.** Every file here exists to give you something real to clone, branch, change, commit, push, review, merge, pull, and (on purpose) conflict over.

## What you'll learn

- Why version control exists
- The difference between Git and GitHub
- The four places your work lives: **working directory → staging area → local repository → remote (GitHub)**
- Cloning a repository and checking it with `git status`
- Working on a branch instead of `main`
- Staging and committing changes with `git add`, `git diff`, and `git commit`
- Pushing your branch and opening a Pull Request
- Reviewing a peer's PR, and responding to review comments
- Merging your work and pulling everyone else's
- Reading merge conflict markers and resolving a real conflict

## Repository workflow

```
clone → branch → create your file → status/diff → stage → commit
→ push → Pull Request → peer review → revise → push again
→ approve → merge → switch to main → pull → conflict lab
```

Each participant creates **one file**, named after their own GitHub username, in `contributors/`. This keeps everyone's normal contribution conflict-free — the only intentional conflict happens later, in `conflict-lab/`.

## Your contribution

1. Clone this repository and `cd` into it.
2. Create your own branch — never work directly on `main`.
3. Copy `contributors/_TEMPLATE.md` into `contributors/<your-github-username>.md` and fill it in.
4. Follow the in-session quest sheet your host provides for the exact command sequence.
5. Open a Pull Request using the template below, get it reviewed, and merge it.

## If you're stuck

- **Run `git status`.** This is the universal first move when you're confused — it tells you exactly what Git sees.
- Read the error message out loud. Most Git errors tell you what to do next.
- Ask a helper — that's what they're there for.
- Panicking mid-merge-conflict? Run `git merge --abort` and you're back where you started.

## Golden rules

- 🧭 **`git status`** when confused
- 🔒 **Never commit secrets**
- 🔁 **Commit ≠ push** — a commit only lives on your laptop until you push it
- ⚔️ **Conflicts are normal** — they don't mean you broke Git
