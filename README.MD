# Node Basics
echo "#Something" >> <FileName.EXT>

git init
git add .
git config --global user.name "<Name>"
git config --global user.email "<email@address.com>"

git commit -m "<Commit Message>"

# Configure npm-global director as your custom directory
mkdir npm-global
cd npm-global
pwd
npm config set prefix /Users/waqas/npm-global
set /Users/waqas/npm-global/bin in your current path
source ~/.bash_profile to load the path

#Connect git remote
git remote add origin <git url>
git push -u origin master