# release_versioning

Task6: Tagging & Release
•	Create a repo release_versioning.
•	Make 3 commits (v1 feature, v2 feature, v3 feature).
•	Tag each commit as v1.0, v2.0, v3.0.
•	Push all tags to GitHub.
•	Share output of git tag -l and screenshot from GitHub showing releases.

steps to be followed
step1: create a repository on github and then clone it to the local machine
--> git clone <url>

Step 2: Create first commit (v1 feature)
--> echo "Feature version 1" > app.txt
--> git add app.txt
--> git commit -m "Added v1 feature"

Step 3: Create second commit (v2 feature)
--> echo "Feature version 2" >> app.txt
--> git add app.txt
--> git commit -m "Added v2 feature"

Step 4: Create third commit (v3 feature)
--> echo "Feature version 3" >> app.txt
--> git add app.txt
--> git commit -m "Added v3 feature"

Step 5: Tag each commit
--> git tag -a v1.0 -m "Release version 1.0"
--> git tag -a v2.0 -m "Release version 2.0"
--> git tag -a v3.0 -m "Release version 3.0"

Step 6: Verify tags
--> git tag -l

Step 7: Push code and tags to GitHub
--> Push your commits: git push -u origin main

--> Push all tags: git push origin --tags

step 8: Verify tags on GitHub
--> On GitHub:

--> Go to your repository → https://github.com/`
    <your-username>`/release_versioning
--> Click the “Tags” link (next to “Releases”)
