## 26 Jan 2026
1. REST API
   - CRUD
      - Create
      - Read
      - Update
      - Delete

2. commands used
  - npm init -y
  - npm install express
  - package.json vs package-lock.json
  - difference between node and nodemon
  - terminal mein sahi message hai but browser mein copilot kyu open ho rha hai?
     - Express server is listening on localhost:3000
     - Other browsers (Chrome/Firefox) send a proper HTTP request
     - Edge intercepts localhost and routes it to Copilot / search
     - Backend never even sees the request
- address bar mein kuch bhi daalne par copilot kyu open ho rha hai?
- hybrid server jo browser ko bhi support kare and mobile apps ko bhi
- jab mere hi system mein server run kar rha hai...toh why is it taking so much time to load? is it because of network or what is reason??

dynamic path variables
put vs patch
postman
npm install -g nodemon
what is present in env file -- environment variables that are not directly present in code but are injected in source code at execution time, this variables cannot be exposed on git version 


which ai tools is best for what?? - best usecase of each ai tool

debugging techniques
-- insert some log statements to check ki kaha tak sahi chal rha hai

windows subsystem for linux (wsl)
ubuntu?
actual mein linux kaam kese kar raha hai wsl mein?
linux, windows, macos ---more detailed

open powershell as admin
run wsl --install

nptel assignments and classes

## 27 Jan 2026
installing wsl and ubuntu
what is linux distro?
wsl --shutdown
wsl --unregister Ubuntu
dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart
what is LTS while installing things?
what is posix socket?
sudo apt update && sudo apt upgrade -y
sudo apt install -y build-essential

code .

documentation after learning is very important - it simplifies the things, enables to systematise concepts which helps to speak clearly about about the same i.e. effective communication
simple things also make memorising easy

explore OneNotes, google NotebookLM

what is fs lib? functions? need? problem solved? usage?
listen, get, require functions...callback function in these
how many ports are there on a machine?...like the beginning of concept of port -> physical, logical and dynamic
use of bodyparser library

task -->
1. create a todo app that let users store todo on server
2. add server and database to expense tracker and todo app
3. implement following usecases of middleware - 1. authentication(input validation)     2. count number of user requests    3. find avg time taken by server to handle requests
4. apply global catches somewhere

todo app 
1. npm init -y
2. npm install express cors.....cors?
3. what is utils?
4. module vs commonjs?
5. compare old code and new code of action.js


## 28 Jan 2026
1. todo app connected to backend - study
2. wsl study

## 29 Jan 2026
1. issue faced while pushing httpserver code on github from ubuntu

## 30 Jan 2026 Friday
1. nlp classes
  - 
2. leetcode problem
  - 
3. adding input validation to todo list task manager
  - agar server band rahega toh kya frontend kaam nhi karega?
  - checkbox frontend par kaam kar rha hai but jese hi reload kar rhe hai checkbox par changes save nhi ho rhe hai
  - how postman can bypass frontend input validation? how frontend input validation is not strong?

  - get is never sent with body