

This map is based on Mapbox and Web.GL. Most parts are written in React and compiled into Javascript. Files are served by Node.js.


## Requirements

In order to run the map, you will have to aquire an API key from Mapbox. It is free: http://mapbox.com. You will have to provide this key to the container that runs the UI. 

## Build me (takes around 15 minutes)

    sudo docker build -t frontend .

## Run me

Don't forget to set your token here.

    sudo docker run -p 3001:3001 -p 3000:3000 -p 6080:6080 -e MAPBOX_TOKEN='token_here' frontend
