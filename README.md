# nodeJsStatic
Step 1 create a folder
2 open cmd in it
3 write npm init
4 hit enter multiple times
5 install express –-save
6 after that open the folder in vs code
7 create app.js file
Const express=require(‘express’);
Const app= express()
App.use(express.static(‘public’))
App.listen(4000,()=>{
Console.log(“server is started”)
})
8 create a public folder
9 inside public folder create index.html
10 write something in it
11 open your terminal again and type
 Node app.js
12 after that open browser and type
 Localhost:4000
