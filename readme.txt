git is a distributed version control system.
git is free software distributed under the GPL.
git basic command as next:
git command:
git init		//init repository
git add "filename"	//add to the staging area
git commit -m "mark"	//add to repository
git status			//query the work area status
git diff			//query the different
git diff HEAD -- readme.txt 	//query the work area and repository different
git log --pretty=oneline	//query log
git reflog		//query history operation
git reset --hard HEAD^		//fallback last version
git reset --hard HEAD^number	//fallback the number version
git reset --hard versionNumber	//fallback the specify version
work area \ stage area \ repository area
git checkout -- filename		//discarded the modify in work area.
git reset HEAD filename  	//discarded the modify in unstage
rm filename		//delete file from work area.
git rm filename 	//delete file from stage area.
ssh-keygen -t rsa -c "youremail"		//create SSH Key
git remote add origin git@github.com:supersky2015/gittest.git 	//connect the remote repository
git push -u origin master		//local push to remote 
git push origin master	//second 
git clone git@github.com:supersky2015/opencv.git 	//clone remote to local 
git branch dev		//create dev branch
git checkout dev	// switched to branch
git checkout -b dev 	//create and switched to branch dev
git branch		//query current branch and view all branchs
git merge dev	//merge dev to current branch
git branch -d branchname	//delete the assigned name branch
git log --graph			//query the merge branch graph
git merge --no-ff -m "merge with no-ff" branchName	//merge branch with no fast forward mode。
git log --graph --pretty=oneline --abbrev-commit 	//query the merge graph
test saved workarea.
git stash		//saved workarea.
git stash apply		//restore the stash 
git stash drop		//delete the stash
git stash pop		//restore the stash then delete
git stash list		//query the stash 
git stash apply stash@{index} 	//restore the stash asseigned.
git branch -D branchname 	//force to delete the branch
git remote		//query the remote info
git remote -v		//query the remote info for details
20181116 FOR pgge 52