# REPO_upd

## HOLA Rushabh, Neeraj!

#### I guess you are here to clone me ;)

#### But have you already added the ssh keys to make ssh cloning possible?
Follow the instructions on the link below: 
https://help.github.com/en/articles/connecting-to-github-with-ssh

If you have a github account and the admin of the repository(which is **tamasigithub** for this repository)
then you can have a look at the contents here:
https://github.com/tamasigithub/REPO_upd

On the right side you will see a green button 'clone or download'

Click on that and copy the link

Next go to the directory where you would like to clone this repository and type
***git clone git@github.com:tamasigithub/REPO_upd.git***
You can either use the ssh link to clone or https. ssh is recomended

#### I just created a new branch ;) 
I did the following to create a new branch:

***git branch tamasi ***

You can list all the branches you have in your repo by doing

***git branch***

It prints the following for me:
\*master
tamasi

To switch to the newly created branch 'tamasi' do
***git checkout tamasi***

You can now create a new test file
***touch test.txt***

***git add test.txt***

***git status***

***git commit -m "hurray my first test text file ;)"***

***git push --set-upstream origin tamasi***

This has now updated your changes to the remote repository -> GO CHECK!

#### To pull updates from the master branch do
***git pull origin master***

if your branch and master branch are different, which might be the case
it will complain saying there is a conflict in some file

you will have to fix this conflict first
There are some instructions here:
https://help.github.com/en/articles/resolving-a-merge-conflict-using-the-command-line

Now it's time to learn how to merge your local branch changes to master

I have'nt done it before.. I am learning too I will do it slowly

if you want to checkout a specific remote branch from a repository

clone the master branch and do :
git checkout --track origin/<name_of_remote_branch>

 
