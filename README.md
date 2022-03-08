# ProProperty
A single page web app created to complete the arithmetic of rental property estimates.

#Starting the project
  A. Install Visual Studio Code
  B. Install Node.js
  C. Install Git
#Creating a Vue Project
  A. Open Git Bash
  B. $ npm install -g @vue/cli
  C. $ vue create {NAME OF PROJECT}
  D. cd into project folder
  E. $ npm run serve
#Creating a RestAPI
  A. mkdir -p {NAME}
  B. cd into {NAME}
  C. $ npm init
  D. Create a index.js file and add the following
  /*
      const express = require('express')
      const app = express()
      const port = 3000

      app.get('/', (req, res) => res.send('Hello World!'))

      app.listen(port, () => console.log(`REST API Started on port ${port}`))
   /
   E. $ npm install --save express
 #Setting up Git
   A. Create a repository on github.com
   B. $ git init (in your project folder)
   C. $ git remote add origin https://github.com/{USER NAME}/{REPO NAME}.git (use the html link)
   D. cd into project folder
   E. $rm -rf .git
   F. $ git add -A
   G. $ git commit -m "{Message}"
   H. $ git push origin {main,master,develop}
