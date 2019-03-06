# ChatRoom
Chat Room Application using MEVN Stack 

### Create Vue Application
npm install -g vue-cli<br>
vue init webpack mevn-chat<br>
cd mevn-chat<br>
npm run dev -> View on browser localhost:8080<br>

### Install Express RESTful API 
npm install --save express body-parser morgan body-parser serve-favicon<br>
mkdir bin<br>
touch bin/www -> Add server port listener<br>
Change package.jason "start": "npm run dev" to "npm run build && node ./bin/www"<br>
Create error handlers on app.js<br>
Create routes chat.js and room.js<br>
npm start -> `http://localhost:3000/api/room` or `http://localhost:3000/api/chat` to see on browser<br>
npm install --save mongoose bluebird<br>
Create mongoose promise to require bluebird (replace uri to variable with your mLab or MongoDB uri connection with user and password)<br>
node ./bin/www or npm start to run project<br>
