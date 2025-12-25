# Pull vs Pull Request vs Push

**Name:** Tannaz Farokhi  
**Student No:** 40233413

---

## Quick Comparison

| | Pull | Push | Pull Request |
|---|---|---|---|
| **Type** | Git command | Git command | Platform feature |
| **Direction** | Remote → Local | Local → Remote | Branch → Branch |
| **Purpose** | Get updates | Share changes | Request review |
| **Command** | `git pull` | `git push` | Web interface |
| **Review?** | No | No | Yes |

---

## Pull

**What:** Downloads changes from remote and merges into local branch  
**Usage:** `git pull`  
**Example:** Get teammate's bug fix to your computer

## Push

**What:** Uploads your local changes to remote repository  
**Usage:** `git push`  
**Example:** Share your bug fix with team

## Pull Request

**What:** Proposal to merge code with review process  
**Usage:** Open via GitHub/GitLab web interface  
**Example:** Request review of your bug fix before merging

---

## Key Differences

**Pull & Push:**
- Git commands for synchronization
- No review process
- Direct operations

**Pull Request:**
- Platform feature for collaboration
- Requires review and approval
- Creates discussion thread

**Important:** Pull Request does NOT use `git pull` command. It's a request for someone to review and merge your changes.

---

## Typical Workflow

```bash
# 1. PULL - Get latest
git pull origin main

# 2. Create branch
git checkout -b fix-bug

# 3. Make changes
git commit -m "Fix bug"

# 4. PUSH - Upload branch
git push origin fix-bug

# 5. PULL REQUEST - Open on GitHub
# (Team reviews)

# 6. After merge, PULL again
git checkout main
git pull origin main
```

---

**Resources:**
- https://git-scm.com/docs/git-pull
- https://git-scm.com/docs/git-push
- https://docs.github.com/en/pull-requests
