# studygit
This is for *studying github* 
I have added some lines here
**Vineesh kalarickal sundaran**

# mark down language tricks
With this markup you can obtain *simple emhpasis* (usually rendered in italic text), **strong emphasis** (usually rendered in bold text), `source code` text (usually rendered in monospaced text), or ~~strikethrough~~ text (usually rendered with a line through text).  

You may use also _this_ or __this__ notation to emphatize text, and you can use all them _**`together`**_ (and you can mix `*` and `_`)  

Tutorials : <https://agea.github.io/tutorial.md/>  
[Tutorial MD](https://agea.github.io/tutorial.md/)


# commands  
`commands i studied for git hub`  
git clone  :: Repository copy download to local directory  
git status :: all the status of git (add / modified)  
git add or git commit -a :: to add the files  
git add . :: add all the files that are changed or added  
git add <filename> :: add specific file  
git restore --staged <filename> :: Restore last commited files  
git config --global user.email "vineesh.kalarickal@gmail.com"  
git config --global user.name "Vineesh Kalarickal"  
git commit -m "Added index.php" -m "This is for description of index php file" :: Files commited locally  

ssh-keygen -t rsa -b 4096 -C "vineesh.kalarickal@gmail.com" :: generate ssh key to push to repository

git push :: push to git hub web repository  

`*Upstream for future - set default origin path so that we can just use *`  
git push -u origin master 
(git push --set-upstream origin feature-readme-instructions)

git branch :: `List all the branches`  
git checkout -b feature :: *creating new branch*  
git checkout master :: *switching from new branch to master branch*  
git push --delete origin old_branch :: Remote path will be deleted    
git branch -d feature-readme-instructions :: local path will be deleted  
git merge master :: *merge to master from the branch*  
git merge --abort :: `abort last merge`  
git diff `branch name` :: show the difference between current branch and the branch name added  
git reset [reset id for go to the specific branch | HEAD~1 for 1 commit back | null for last commit undo]  
git log :: for all the log  

git pull command study


If you need to remove a single file from the staging area, use

git reset HEAD -- <file>

If you need to remove a whole directory (folder) from the staging area, use

git reset HEAD -- <directoryName>

# Local development
1. Open index.php in your browser  
2. Added html syntax
3. header changed
