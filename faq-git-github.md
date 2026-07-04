# FAQ: Git and GitHub

## General

**Q: What is the difference between Git and GitHub?**  
A: Git is a version control tool that runs on your local machine. GitHub is a cloud service that hosts Git repositories and enables collaboration.

**Q: Do I need GitHub to use Git?**  
A: No. Git works entirely on your local machine. GitHub is optional, but recommended for backup and sharing.

---

## Common Errors

**Q: I see `fatal: not a git repository`. What does it mean?**  
A: You are running a Git command outside of a Git repository. Run `cd your-project-folder` first.

**Q: Why can't I push with my GitHub password?**  
A: GitHub stopped supporting password authentication in 2021. Use a Personal Access Token (PAT) instead.

---

## Best Practices

**Q: How often should I commit?**  
A: Commit when you complete one logical unit of work — not too often, not too rarely. A good rule: if you can describe the change in one sentence, it is ready to commit.

**Q: What makes a good commit message?**  
A: Start with a verb (`add`, `fix`, `update`), keep it under 72 characters, and describe what changed and why.