# Arma Reforger Workbench Project

This repository contains collaborative work on Arma Reforger using the **Enfusion Workbench**.  
We use a **branching workflow** to keep `main` stable while still allowing everyone to contribute.  

---

## 1. Install GitHub Desktop
We’ll be using GitHub’s GUI client to simplify version control.

1. Download GitHub Desktop: [https://desktop.github.com](https://desktop.github.com)  
2. Install and sign in with your GitHub account.  

---

## 2. Clone the Repository
1. Open **GitHub Desktop**.  
2. Go to **File > Clone Repository…**  
3. Paste the repository URL:  
   ```bash
   https://github.com/<YourOrg>/<RepoName>.git
   ```
4. For the **local path**, choose your Arma Reforger projects folder. Typically:  
   ```bash
   Documents/My Games/ArmaReforger/Workbench/Projects
   ```
5. Click **Clone**.  

---

## 3. Create Your Own Branch
We work on **feature branches** so that the `main` branch always stays stable.

1. In GitHub Desktop, click the **Current Branch** dropdown.  
2. Select **New Branch…**  
3. Name your branch something descriptive, e.g.:  
   ```
   feature-new-terrain
   fix-entity-spawn
   balance-vehicle-loadouts
   ```
4. Click **Create Branch**.  

---

## 4. Make Changes in Enfusion Workbench
1. Open **Enfusion Workbench**.  
2. Open the project you just cloned.  
3. Make your changes (terrain edits, entities, scripts, etc.).  
4. Save and test your work.  

---

## 5. Commit and Push Changes
1. Switch back to **GitHub Desktop**.  
2. You’ll see your changed files listed.  
3. Write a short summary of what you did, e.g.:  
   ```
   Added new spawn points to Arland terrain
   ```
4. Click **Commit to [your branch name]**.  
5. Click **Push origin** to upload your branch to GitHub.  

---

## 6. Submit a Pull Request (PR)
1. In GitHub Desktop, click **Create Pull Request** (after pushing).  
   - Or go to the repo on GitHub.com and click **Compare & Pull Request**.  
2. Fill in details about what your change does.  
3. Submit the PR.  

**Important**: All changes must come through PRs — the `main` branch is protected.  

I’ll review your PR, provide feedback if needed, and merge it into `main` when ready.  

---

## Workflow Summary
- **Never commit directly to `main`**.  
- Always create a **new branch** for each feature or fix.  
- Commit + push changes to your branch.  
- Open a **PR** → review → merge into `main`.  

---
