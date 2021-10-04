npm init -y
npx gitignore node
git init
git status
ls -lah
  (to see the hidden .git folder created)
npx eslint --init

√ How would you like to use ESLint? · check syntax and find problems    
√ What type of modules does your project use? · commonjs
√ Which framework does your project use? · none
√ Does your project use TypeScript? · No
√ Where does your code run? · node
√ What format do you want your config file to be in? · JSON
Local ESLint installation not found.
√ Would you like to install them now with npm? · Yes

npm i -D nodemon (install --save-dev)

-Create README.md

-Open git tab
CNTRL+ENTER (to do both git add . AND git add commit -m "message")

-OR just:
git add .
git commit -m "message"

-Then:
git checkout -b main

-Create public remote github repo (leave all options unchecked)
git remote add origin https://github.com/JoshuaHolloway/api-4.git

-Push:
git push origin main
  --Do NOT do: git push -U origin main, etc.
  --Be explicit where it is we are pushing to.
  --We are pushing to the remote called 'origin'
  --What are we pushing?  A.) The 'main' branch

-Refresh public repo
  --Default branch should be main and base project should be uploaded.
  --Aparenetly, the master branch is overidden by main.

==============

npm install --save express cors helmet dotenv

==============
-Add scripts
"server": "nodemon index.js",
"start": "node index.js"

==============
-terminal commands:
--------------
env
--------------
node
console.log(process.env);
console.log(process.env.PATH);
-------------


==============
-Create .env file
PORT=9000
LADY=gaga
SECRET="this 42"

==============
-Create config.js
module.exports = {
  PORT: process.env.PORT || 5e3,
};