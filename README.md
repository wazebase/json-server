To use json server, run following command: 

npm install -g json-server

Then, start json server with:

json-server --watch db.json

Now you should be able to access via http://localhost:3000/parcel and http://localhost:3000/contact to json data. 

If you want to access localhost from web, you would also need to run these 2 commands:

npm install -g localtunnel

And 

lt --port 3000

After this, your json-server should become available on Web after you let Localtunnel know your IP adress (you'll see the instruction on generated web page on how to do it)
