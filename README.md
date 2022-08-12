# The hash creates a header

md means 'mark down' and is a basic way to format text in this kind of file. 
Yuo can edit the file and then commit it. The full list of commits (updates) are available to see.

#Sub header created in VS code

I had to connect my public key to github so that I can commit to git via VScode. I do this via the bash terminal on VScode.

# Commands I used:

git status shows all files that were created, updated or deleted (untracked files are not being tracked by git)
git add . (the space before the full stop is important) will tell gip to track ALL changes in the untracked and modified sections of anything you see after git status.
Optionally, you can use something like add index.html to have git track one specific file or folder.
git commit -m "insert ESSENTIAL message here to explain the commit" -m"add an optional description for the description box here" will commit changes to git.
git push will push the code live to a remote repository where the project is hosted (i.e. github)
