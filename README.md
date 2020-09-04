Welcome to My Places App.

This App was built with Node JS Express on the backend, and with React on the frontend.

With this App you can register a user, log in, and post your own places with images.

To run the project run npm install in the root of the frontend directory, as well as the root of the backend directory.

Then, run npm start on both root directories.

Then, edit the .env file in the Frontend directory with our own Google Geo location API key, so that the map displays correctly your added place.

Finally, edit the nodemon.json file in the Backend directory and add your own Mongo DB Atlas credentials so that the app correctly connects to a remote mongo db database, also add your Google Geo location API key, and a JWT secret string 
