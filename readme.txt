git is a distributed version control system.
git is free software distributed under the GPL.
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