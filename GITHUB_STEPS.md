# GitHub қадамдары
GitHub-та `computer-repair-center` атты бос Public репозиторий ашыңыз.

Git Bash-та осы папкаға кіріп, командаларды бір-бірден орындаңыз:

```bash
git init
git branch -M main
git config user.name "Ali Nurmakhambet"
git add README.md
git commit -m "Add project README"
git switch -c behavior-diagrams
git add docs/analysis/activity-create-repair-request.*
git commit -m "Add activity diagram"
git add docs/analysis/sequence-create-repair-request.*
git commit -m "Add sequence diagram"
git add .gitignore GITHUB_STEPS.md
git commit -m "Add project documentation"
git switch main
git remote add origin https://github.com/USERNAME/computer-repair-center.git
git push -u origin main
git switch behavior-diagrams
git push -u origin behavior-diagrams
```

`USERNAME` орнына Әлидің GitHub логинін қойыңыз. GitHub-та `Compare & pull request` → `Create pull request` → `Merge pull request` → `Confirm merge`. Соңында `git switch main` және `git pull origin main`.
