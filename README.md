
# Git Cheat Sheet
# Writer Intro
I am **Subham Maity**
I love Programming. One of the aims I had when I started ```CodeXam``` was to make learning programming easy.
## Help us improve this guide - **Fork, Pull Requests, Shares and Likes are recommended**!



[1]()
 
# **git**
(instruction)


[2]()
# **pwd**
(Print Working Directory: Prints out the current directory )

[3]()
# **cd**
(Change Directory: To change this current working directory)

[4]()
# git config --global user.name &quot;FIRST\_NAME LAST\_NAME&quot;
(Set your username)

[5]()
#git config --global user.email &quot;MY\_NAME@example.com&quot;
(Set your Email)

[6]()
# **git status**
(The git status command displays the state of the working directory and the staging area)

[7]()
# **git init**
(The git init command creates a new Git repository)

[8]()
# **git add –a**
or
# **git add -A**
(Stages all changes)

[9]()
# **git add .**
(stages new files and modifications, **without deletions** (on the current directory and its subdirectories)

[10]()
# **git add -u**
(stages modifications and deletions, **without new files** )

[11]()
# **git commit -m &quot;your comment&quot;**
(The -m stands for message. When calling git commit , it is required to include a message.)

[12]()
# **git log**
(The git log command displays a record of the commits in a Git repository.)

[13]()
# **git add File\_Name\_Example.txt**


The git add command is used to add file contents to the Index (Staging Area)

[14]()
# **ls**
(The Bash command ls is used to &#39;list&#39; contents of the current working directory. ls is equivalent to DIR on a Windows console host terminal)

[15]()
# **git clone** [# **github.com/tensorflow/tensorflow.git**](https://github.com/tensorflow/tensorflow.git) 

(git clone is primarily used to point to an existing repo and make a clone or copy of that repo at in a new directory, at another location)

[16]()
# **rm -rf .git**
(Delete all the connection or entire repo)

[17]()
# **touch file.extension**

#
(Touch command allows to create a blank file example: flie.log)

[18]()
# **touch .gitignore**
(.gitignore file is a text file that tells Git which files or folders to ignore in a project)

# \*
is used as a wildcard match and ignores all files. Example: \*.extension , \*.log

# /
is used to ignore path names relative to the .gitignore file.Example: /dir

# **#**
is used to add comments to a .gitignore file.Example: #something

[19]()
# **git diff**
(Diff command is used in git to track the difference between the changes made on a file)

[20]()
# **git diff –staged**
(git diff --staged will only show changes to files in the &quot;staged&quot; area.)

[21]()
# **git commit -a -m &quot;Commit Message&quot;**
(skip the staging and directly commit.)


[22]()
# **git rm filename.extension**
(git rm is used to remove a file from a Git repository.)

[23]()
# **git mv filename.extension renamefile.extension**
(It will rename the file from filename.extension to renamefile.extension. And it will also get automatically staged by git. All we need to do is commit (mv means move) you can move by mv comment)

[24]()
# **git rm –cached file.extension**
(It will remove that file from the tracker and it will become an untracked file.)

[25]()
# **Tab Key on the keyboard**
(Use Tab Completion to Type Commands Faster on Any Operating System.)

[26]()
# **git log -p**
(It will show what has been changed on a commit.)

# **git log -p -2**
(for seeing the last 2 changes.)

[27]()
# **git log --stat**
( we can get a brief summary of commits by typing.)

[28]()
# **git log --pretty=oneline**
(If you want to see the commits on one line then type)

[29]()
# **git log --pretty=short**
(If you just want to see the commits and The author then use .)

[30]()
# **git log --pretty=full**
( if you want a little bit more info like who is the committer, commit message.)

[31]()
# **git log --since=2.weeks**
(If you want to filter commits by time.To see the last 2 months)

# **git log --since=2.days**
(To see the last 2 days)

# **git log --since=2.weeks**
(To see the last 2 weeks)



[32]()
# **git log --pretty=format:&quot;%h -- %an&quot;**
(We can format the output by using the formatting codes provided in [Git&#39;s](https://git-scm.com/docs/pretty-formats)(details) website. For an example we can use this format to print just the author name and the hash.)

[33]()
# **git config --global core.editor notepad**
(you can easily configure git to use another editor. [All Code Editor](https://git-scm.com/book/en/v2/Appendix-C%3A-Git-Commands-Setup-and-Config))

[34]()
# **git commit --amend**
(Now to change a commit. So, to change the most recent commit . Then an editor will open where you can change the commit message. All you need to do is change the message and then you need to close it by pressing i then esc key then type &quot;
# **:wq**
&quot; to exit the editor. Now you have successfully edited the commit (60).[Details ( 7. Git Log: Viewing &amp; Changing \&gt;](https://docs.google.com/document/d/190sAY4DDUiqnZRU8ZprLMTd_6e3r3i9aOdA-26l5IYo/edit#heading=h.fl7q6mu8tu3a)[**Customized Commit Output )**](https://docs.google.com/document/d/190sAY4DDUiqnZRU8ZprLMTd_6e3r3i9aOdA-26l5IYo/edit#heading=h.fl7q6mu8tu3a) )

[35]()
# **git restore --staged file.extension**

#
(It will unstage the file and you can verify it by using &quot;git status).

[36]()
# **git checkout -- file.extension**

#
(let&#39;s say we have modified the unstaged file and made some changes which were not necessary. Now the program is not working. So we have to restore that file to its previous state where it was working)

[37]()
# **git checkout -f**
(To restore your entire working directory to the previous commit . It will restore your entire directory to the last commit. )

[38]()
# **git remote add origin git@github.com:yourusername/repositoryname.git**

#
(We have a git repo in our local system we just want to push it to the remote system then copy the code on git&#39;s website which looks like this: &quot;git remote add origin git@github.com:yourusername/repositoryname.git&quot;and paste it to the git bash and press enter. )

[39]()
# **Shift+Insert Key**
(Paste Text On the terminal)

[40]()
# **git push -u origin master**
(this command which pushes the files onto the remote server)

[41]()
# **ssh-keygen -t rsa -b 4096 -C &quot;your\_email@example.com&quot;**
(Now just simply press enter 3 times)

# **eval $(ssh-agent -s)**
(Now run this command)

# **ssh-add ~/.ssh/id\_rsa**
(Now run this )

# **tail ~/.ssh/id\_rsa.pub**
(Now it will show you the **ssh** key ) ([Details:9.Remote Repositories](https://docs.google.com/document/d/190sAY4DDUiqnZRU8ZprLMTd_6e3r3i9aOdA-26l5IYo/edit#heading=h.z8n0twn6f4b8))

[42]()
# **git remote -v**
(List the current remotes associated with the local repository.)

[43]()
# **git remote add [name] [URL]**
(Add a remote.)

[44]()
# **git remote remove [name]**
(Remove a remote.)[Details](https://github.com/git-guides/git-remote)

[45]()
# **git config --global alias.st status**
(Alias is a term which is associated with shortcuts in Git. It shortens the long commands to increase efficiency Type &quot;git config --global alias.st status&quot; and press enter. Now what it means is if we type &quot; **git st**&quot; it will give us the output of &quot;git status&quot;)

# **git config --global alias.ci commit**
(Type &quot;git config --global alias.ci commit&quot; and press enter. Now what it means is if we type &quot; **git ci**&quot; it will give us the output of &quot;git commit&quot;)

# **git config --global alias.unstage &#39;restore --staged --&#39;**
(Type &quot;git config --global alias.unstage &#39;restore --staged --&#39;&quot; and press enter. Now what it means is if we type &quot; **git unstage** file.extension&quot; it will give us the output of &quot;git restore --staged file.extension&quot;) [Details](https://docs.google.com/document/d/190sAY4DDUiqnZRU8ZprLMTd_6e3r3i9aOdA-26l5IYo/edit#)[(10.Setting Alias)](https://docs.google.com/document/d/190sAY4DDUiqnZRU8ZprLMTd_6e3r3i9aOdA-26l5IYo/edit#)

# **git config --global alias.last &#39;log -p -1&#39;&#39;**
(Type &quot;git config --global alias.last &#39;log -p -1&#39;&#39;&quot; and press enter. Now what it means is if we type &quot; **git last**&quot; it will give us the output of &quot;git log -p -1&quot;)

[46]()
# **git checkout -b branchname**

#
(creates a new branch and checks out the new branch while git branch BRANCH\_NAME creates a new branch but leaves you on the same branch.)([Details 11.Creating Switching Branches](https://docs.google.com/document/d/190sAY4DDUiqnZRU8ZprLMTd_6e3r3i9aOdA-26l5IYo/edit#heading=h.mr8ccprk4t3i))

[47]()
# **git checkout master**
(You can just checkout a remote tracking branch directly, with git checkout origin/master . This is similar to checking out a local branch as you would with git checkout master , but the difference is that any commits you make won&#39;t update master.)([Details 11.Creating Switching Branches](https://docs.google.com/document/d/190sAY4DDUiqnZRU8ZprLMTd_6e3r3i9aOdA-26l5IYo/edit#heading=h.mr8ccprk4t3i))

[48]()
# **git checkout branchname**

#
(You can just checkout your create branch.)([Details 11.Creating Switching Branches](https://docs.google.com/document/d/190sAY4DDUiqnZRU8ZprLMTd_6e3r3i9aOdA-26l5IYo/edit#heading=h.mr8ccprk4t3i))

[49]()
# **git merge branchname**
(Merging Branches in a Local Repository)

[50]()
# **git branch --merged**
(If you want to see which branches were merged then use)

[51]()
# **git branch --no-merged**
(If you want to see which branches were not merged then use)

[52]()
# **git branch -d branchname**
(To delete a branch we need to use.Note that this command will fail if the branch we are deleting has not merged to the main branch)

[53]()
# **git branch -D branchname**
(To delete a branch we need to use &quot;git branch -d branchname&quot;. Note that this command will fail if the branch we are deleting has not merged to the main branch. To tackle this error we will use &quot;git branch -D branchname&quot;, it will delete the branch even if it&#39;s not even merged yet.

[54]()
# **git branch -d origin branchname**
( We will delete the unnecessary branch )

[55]()
# **git branch -d origin branchname**
( We will delete the unnecessary branch )

[56]()
# **git push origin branchname/master**

#
( , it will push that branch to github and we can check that on github. )

[57]()
# **git push origin branchname/master**

#
( , it will push that branch to github and we can check that on github. )

[58]()
# **vi filename.extension**

#
( open vim editor )

[59]()
# **cat filename.extension**
( cat command allows us to create single or multiple files, view content of a file, concatenate files and redirect output in terminal or files. )

[60]()
# **VimEdit in terminal:**

# **vi file.extension**

For edit type anything

Press the
# **ESC**
key. You should see the ––INSERT–– label vanish from the lower-left. To save your changes before you exit, type
# **:w**
, and then Enter. This will save any changes made. ... To exit Vi/Vim, type
# **:q**
and hit Enter. If you want to save and exit both
# **:wq**
