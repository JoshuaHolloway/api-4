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

-Open git tab
CNTRL+ENTER (to do both git add . AND git add commit -m "message")

-Create public remote repo (leave all options unchecked)
git remote add origin https://github.com/JoshuaHolloway/api-4.git
git push origin master

-Instructions were to do:
git checkout -b main
git push origin main
  --Do NOT do: git push -U origin main, etc.
  --Be explicit where it is we are pushing to.
  --We are pushing to the remote called 'origin'
  --What are we pusing?  A.) The 'main' branch



==============
-Create README.md

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
-------------