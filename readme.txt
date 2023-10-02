
Nothing personal

git add ===>working dir to staging area
git commit ====> staging area to local repository
git push ===> local repository to online repository
----------------------------------------------------------------------------
Initialize repository		:	git init
Add files to staging area 	:	git add file_name
Commit to lozal repository	:	git commit -m "first commit"
Rename 'master' branch to main:	git branch -M main
Connect remote repository	:	git remote add origin <repository_link>
							eg:-git remote add origin https://github.com/Harishs2023/new-project.git
Push all changes			:	git push -u origin main
----------------------------------------------------------------------------

https://github.com/Harishs2023/new-project.git

Hello world

git config --global user.email "siddula.harish@gmail.com"
git config --global user.name "Harishs2022"
git config --list
git --version

git diff <1st commit id> <2nd commit id>      =====>shows difference b/w 2 commits
git stash ====>to save something for temporary purpose. It saves in some other folder
git stash list ===>shows all stash changes
git restore <filename> ===> restored from previous commit

git branch <branch name> ===> Creates branch
