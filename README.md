# Nodejs-Basic Note Taking App

[![Join the chat at https://gitter.im/nodejs-note-taking-app/community](https://badges.gitter.im/nodejs-note-taking-app/community.svg)](https://gitter.im/nodejs-note-taking-app/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

###### nodejs, ejs, mongodb, scss, bulmacss

First of All a huge shout-out to Facebook Developer Circle Raipur for organising a Node.js workshop on 23rd February 2019.

One of the things that was highlighted during the workshop was __To build a Note Taking CRUD app using MongoDB, EJS, Express.js and Node.js__

The process is straight forward
## Step 1
Clone the repo or download zip
```
git clone https://github.com/arkRedM/nodejs-note-taking-app.git
```
## Step 2
Installing yarn

Depending on the type of OS you use find the instructions to install yarn here:

 https://yarnpkg.com/lang/en/docs/install

Install dependencies using
```
yarn install
```
 ## Step 3
 Create an Online MongoDB on https://mlab.com/  detailed instructions found here:

 https://docs.mlab.com/

 ## Step 4
 Obtain the Standard Connection String and replace the index.js file constant

 ```
let dev_db_url = 'mongo-db-url' // your mlab Standard Connection String
```

## The result
Run the application using
```
yarn start
```

then goto ```http://localhost:8000/``` and explore.

### Scope:
1. Authentication method to manage Individual User Notes.
2. Sharing Notes among users as a basic feature.

Please do Raise Issues and PR's are always welcome (ᵔᴥᵔ)
