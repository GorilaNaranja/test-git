# TEST-GIT

Conflict **1** from develop
Conflict **1** from feature/merge-conflict

Conflict **2** from develop
Conflict **2** from feature/merge-conflict

Conflict **3** from develop
Conflict **3** from feature/merge-conflict

Hey im the second developer

###### 1. Create develop branch.

Created new branch "develop" from master.

```bash
git checkout -b develop
```

###### 2. Create feature branch

Created new branch "feature/create-feature-branch" from develop.

```bash
git checkout -b feature/create-feature-branch
```

###### 3. Create commit and push to feature branch

Created new commit and push to feature branch.

```bash
git status
git add README.md
git commit -m "My commit feature"
git push
```

Maybe should do this:

```bash
git push --set-upstream origin feature/create-feature-branch
git push
```

###### 4. Merge feature branch to develop

Pull Request.

```bash
git checkout develop
git merge feature/create-feature-branch
```
