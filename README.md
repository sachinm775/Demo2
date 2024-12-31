# Demo2
experiment2
<br>
# Step 1: Switch to the master branch
git checkout master

# Step 2: Create and switch to the feature-branch
git checkout -b feature-branch

# Step 3: Make changes, then stage and commit them
git add .
git commit -m "Your commit message for feature-branch"

# Step 4: Switch back to the master branch
git checkout master

# Step 5: Merge feature-branch into master
git merge feature-branch

