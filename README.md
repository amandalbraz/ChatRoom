# ChatRoom
Chat Room Application using MEVN Stack 

### Create Vue Application
npm install -g vue-cli
vue init webpack mevn-chat
cd mevn-chat 
npm run dev -> View on browser localhost:8080

### Install Express RESTful API 
npm install --save express body-parser morgan body-parser serve-favicon
mkdir bin
touch bin/www -> Add server port listener 
Change package.jason "start": "npm run dev" to "npm run build && node ./bin/www"
Create error handlers on app.js
Create routes chat.js and room.js
npm start -> `http://localhost:3000/api/room` or `http://localhost:3000/api/chat` to see on browser
npm install --save mongoose bluebird
Create mongoose promise to require bluebird (replace uri to variable with your mLab or MongoDB uri connection with user and password)
node ./bin/www on main cmd window to 
