 Building web app using react.js, express.js, node.js and mongodb

Prerequisites
In order to get the most out of this project I myself would suggest you to have some familiarity with node.js, react.js and express.js is expected. 
You need to have node installed in your system, everything else we will install as below.

Project Setup

Command prompt command lines after INSTALLING NODE 

----FOR FRONT END THESE ARE NEEDED ----
1) npm install -g gulp bower nodemon
2) mkdir project
3) npm init
4) bower init
5) npm install --save browserify reactify vinyl-source-stream gulp react react-dom express guid
6) bower install --save bootstrap-css

----FOR BACKEND THESE ARE NEEDED----
7) npm install mongoose --python=python2.<span class="code-digit">7</span> --save
8) npm install body-parser --save
9) npm install underscore --save 
10) npm install jquery --save
11) npm install es6-promise --save


After all commands are given

------this one is for mounting the server-------
12) nodemon .\server\server.js

Now please launch your application using following command, and browse http://localhost:7777/index.html but before that lets start our MOngoose db instance

step1:- open your command prompt

step2:- then type cd c:\program files\mongodb\server\3.4\bin (mongodb default location in c: drive, using above command we going to access) if you are using earlier version 2.0,2.6 means you should follow cd c:\program files\mongodb 2.6 standard\bin

step3:- now you were inside mongodb file location, nxt is to create one new directory using command mkdir data.
-----imp steps----
step4:- type mongod --dbpath data (it will connect to port)

step5:- minimize the current command prompt and open another command prompt with "run as admin"

step6:- then type cd c:\program files\mongodb\server\3.0\bin

step7:- now type mongo localhost/schoolfinder (connect to db server)
------imp steps done here----
go to mongo prompt in downloaded files from mongoose db website

"show collections" command is use to display the existing collection in db server
"help" for help
"show dbs" command display schema 





