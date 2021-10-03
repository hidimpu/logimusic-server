# LogiMusic Server 
This is the code for LogiMusic Server deployed on Heroku.
 [![Website perso.crans.org](https://img.shields.io/website-up-down-green-red/https/perso.crans.org.svg)](https://logimusic-server.herokuapp.com/)
# Steps to configure
  To configure the LogiMusic Server you require 3 major parameters' from the spotify developer account. You require following parameters - 
  - CLIENT_ID
  - CLIENT_SECRET
  - REDIRECT_URI

Visit the below url to configure your server.
 https://developer.spotify.com/documentation/web-api/
 - Create a .env file and paste these values.
   ```
   CLIENT_ID= 
   CLIENT_SECRET=
   REDIRECT_URI=
   ```


   Refer to <a href = "https://bit.ly/3Fe5WOH"> this link </a> to know how to get them.
    
## Instructions to run on local server
- Paste the following commands into preferred terminal.
```
git clone https://github.com/hidimpu/logimusic-server.git
```
```
cd logimusic-server 
```
```
npm i 
```
```
node server.js
```
<hr>

Credits - 
- [Parth Shukla](https://github.com/hidimpu)
- [Swapnil Soni](https://github.com/SwapnilSoni1999)
- [Adarsh Chakraborty](https://github.com/adarsh-chakraborty)
- [Rahul](https://github.com/rahul7400)