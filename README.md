# Postman

Using the db.json to simulate as response is easy

1- install nodejs/npm

2- install json server & newman     
$ npm install -g json-server
$ npm install -g newman

3- save db.json in local

4- start the json server   
$ json-server --watch db.json

5- one can run the newman using
newman run <collection file>  -r <reporter>
