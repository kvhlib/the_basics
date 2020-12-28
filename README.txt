1. How to add an existing vs code project to git and github
2. How to do commit and push whenever changes happen
3. How to clone from github to vscode
4. How to remove project from git 

youtube url: https://www.youtube.com/watch?v=Fk12ELJ9Bww

Step 1: Install git on your system
Step 2: Create account on github - https://github.com/
Step 3: Create a repository on github and copy url
Step 4: Go to VS and open project / folder
note: check git is enabled from settings 
Step 5: Goto source control section and click on git icon
Step 6: Give commit message & Commit the changes
Step 7: Add remote repository (github repo) (View -> Command Pallet...-> chọn Git: Add Remote nhập https://github.com/kvhlib/the_basics.git)
Step 8: Push committed changes to github repository
Step 9: check changes on github repos

-- nếu có lỗi thì xử lý như bên dưới

> git -c user.useConfigOnly=true commit --quiet --allow-empty-message --file -

*** Please tell me who you are.

Run

  git config --global user.email "hongkiet@gmail.com"
  git config --global user.name "kvhlib"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: no name was given and auto-detection is disabled
> git config --get-all user.name