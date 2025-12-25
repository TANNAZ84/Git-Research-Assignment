# Pull

**Name:** Tannaz Farokhi  
**Student No:** 40233413

---

## What is Pull?

Fetches changes from remote repository and automatically merges them into your current local branch.

**Command:** `git pull`

## How It Works

Combines two operations:
1. `git fetch` - Downloads changes
2. `git merge` - Merges into local branch

## Key Points

- Downloads updates FROM remote TO local
- Automatically merges into current branch
- Keeps you synchronized with team
- Can cause merge conflicts

## When to Use

- Before starting new work
- Before pushing your changes
- Regularly when working with a team
- After teammates push important changes

## Example

```bash
# Get latest changes
git pull

# Make your changes
# ...

# Pull again before pushing
git pull

# Push your work
git push
```

---

**Resources:**
- https://git-scm.com/docs/git-pull
- https://www.atlassian.com/git/tutorials/syncing/git-pull
