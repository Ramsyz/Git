## Git
First downlaod git from website, after that
In terminal
git --version --> shows git version

git config --global --list
provide the username, emailid

type: q+enter to exit 
##### Change user name 
git config --global user.name yourname

##### Change user email 
git config --global user.email youremail

Now configuration is done.....

#### Create local repo
git init ---> initialize the project
git init project name --> displays initilazed
Type ls --> check your project name

By default if you initialize git repo, first branch--> master branch is created

To commit first create a file in editor,ide
In terminal, 
git commit -m message --> git ommit -m first commit

To check commit
git log --> displays message
now your project is in local machine

If you want to make it remote, in github add new repo 
copy the push existing repo line 

##### Push the existing repo from terminal
git remote add origin https://github.com/........
Next push master branch to origin url
git push -u origin master ---> shows message as done.
now our local master and remote master are connected.
Next go to github and refresh github we can see our changes are published.

We can edit readme file in github and submit committed changes. 
To pull changes to local master/machine --> git pull

##### Git clone
to clone git to editor,ide
In github in project click on clone button & copy url
git clone url --> create in new floder

##### Create new branches
In terminal 
git branch branch name
To check it--> git checkout branch name 
now it shows new branch
