# Git Experiment – Basic Git Commands

## Aim
To understand and implement basic Git commands for version control.

## 1. Create a Git Repository
```bash
mkdir GitExperiment
cd GitExperiment
git init
```

## 2. Create a File
```bash
echo "Hello, this is my first Git experiment." > index.txt
```

## 3. Check Repository Status
```bash
git status
```

## 4. Add Files to Staging Area
```bash
git add index.txt
```

## 5. Commit Changes
```bash
git commit -m "First commit"
```

## 6. View Commit History
```bash
git log --oneline
```

## 7. Modify the File
```bash
echo "Learning Git version control." >> index.txt
git add .
git commit -m "Updated index file"
```

## 8. Create and Switch Branch
```bash
git branch feature
git switch feature
```

## 9. Add and Commit Feature
```bash
echo "This is a feature branch." > feature.txt
git add .
git commit -m "Added feature file"
```

## 10. Merge Branch
```bash
git switch main
git merge feature
```

## 11. Display Branches
```bash
git branch
```

## Learning Outcomes
- Learned to initialize Git repositories.
- Understood staging and committing.
- Learned branch creation and switching.
- Practiced merging branches.
- Understood basic version control operations.
