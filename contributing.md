# Contributing to PBS Ops (Private Repo)

This document applies to the private repo: https://github.com/ProbuiltStructures/pbsops

If you do not have access yet, see README.md in this public repo (pbsops-dms-docs) and submit an access request Issue.

---

## Approved Developer Workflow

1) Accept your invite to the private repo: https://github.com/ProbuiltStructures/pbsops

2) Create your own fork of the private repo (Fork button).

3) Clone your fork to your computer (GitHub Desktop → File → Clone Repository → paste your fork URL).

4) Create a feature branch for your work. Use a clear name:
   feature/<short-description>
   examples:
   • feature/add-asset-tracking
   • feature/fix-quote-rounding

5) Make changes locally, test locally.

6) Commit and push to your fork (GitHub Desktop: Commit → Push origin).

7) Open a Pull Request (PR) from your fork to the private repo:
   • Base repo: ProbuiltStructures/pbsops
   • Base branch: develop
   • Compare branch: your feature branch

8) Fill in the PR description with:
   • What changed (summary)
   • How to test (steps)
   • Screenshots if UI changed
   • Any migration or special notes

9) Wait for review. Address any comments, push updates to the same branch. A core maintainer will merge to develop when approved.

10) Production deploys happen only from the main branch. Core maintainers handle merging develop → main.

---

## Rules

• Never commit secrets (passwords, API keys, wp-config.php, .env).  
• Work only in feature branches (not directly on develop or main).  
• Keep commits small and descriptive.  
• Follow existing code style and structure.  
• Confirm you tested locally before opening a PR.  
• Use Issues/Discussions for questions or to flag blockers.

---

## Branches

• main    → production (locked; deploys to live)  
• develop → staging (approved PRs land here first)  
• feature/* → your work branches (fork → PR into develop)

Thank you for contributing.
