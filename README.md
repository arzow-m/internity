# internity

### GitHub Cheat Sheet for Collaboration
```
# ✅ Clone the repository
git clone https://github.com/your-username/your-repo.git
cd your-repo

# ✅ Create and switch to a new branch
git checkout -b feature/your-feature-name

# ✅ Make changes to your files...

# ✅ Stage your changes
git add .

# ✅ Commit your changes with a message
git commit -m "Add: your short description here"

# ✅ Push your branch to GitHub
git push origin feature/your-feature-name

# ✅ Go to GitHub and open a Pull Request (PR)
#    → GitHub will suggest "Compare & pull request"
#    → Write a title and description, then submit

# ✅ After your teammate reviews and approves the PR, you or they can merge it

# ✅ To update your local main branch:
git checkout main
git pull origin main

# ✅ To delete the feature branch locally and remotely after merging:
git branch -d feature/your-feature-name
git push origin --delete feature/your-feature-name
```
