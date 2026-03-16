git --version
git init
git remote add origin https://github.com/aman782006/test.git
git remote -v

Username & Email
If you want to store configuration globally
git config user.name "Mohd Aman"
git config user.email "mohdaman273016@gmail.com"

To see the configuration 
git config --list

To see current status
git status

Add the current directory to the git
git add .

By Default ( master / main )

To rename the branch
git branch -M dev

git reset --hard commitref
git push origin dev --force

git config --unset user.name
git config --unset user.email




