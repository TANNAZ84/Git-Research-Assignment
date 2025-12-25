# Clone

**Name:** Tannaz Farokhi  
**Student No:** 40233413

---

## What is Clone?

Downloads a complete copy of a repository to your local computer with all history, branches, and files.

**Command:** `git clone <url>`

## Key Points

- Creates local copy on your hard drive
- Includes direct connection to remote (called "origin")
- Work offline and make changes locally
- Sync with remote using `git pull` and `git push`
- Can push if you have write permissions

## When to Use

- Working on a project locally
- After forking to get code on your machine
- Team collaboration on shared repository

## Under the Hood

When you clone:
1. Creates local directory with `.git` folder
2. Downloads all objects (commits, files, trees)
3. Compresses data using zlib
4. Configures "origin" remote pointing to source
5. Checks out default branch
6. Sets up tracking branches

**The `.git` directory** contains all repository data, commit history, and configuration.

---

**Resources:**
- https://git-scm.com/docs/git-clone
- https://www.freecodecamp.org/news/git-internals-for-curious-developers-a1e44e7ecafe
