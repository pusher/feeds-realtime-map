# Pusher Feeds Realtime Map Demo
Demo application showing how Feeds can be used to create realtime updating maps. Location data is sent to clients, and is then rendered on a map.

## Setting the project up

* Clone the repo
* Add your Feeds instance ID and application key to Server/index.js 
* Add your Feeds instance ID to Client/app.js 
* Add your Google Maps API Key to Client/index.html (You can obtain this from https://developers.google.com/maps/documentation/javascript/get-api-key)
* Run ```npm install``` within the 'Server' folder
* Run ```npm start``` in the 'Server' folder.
* Visit http://localhost:3000/ in the browser!