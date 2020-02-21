# This is a full stack application which logs all the places you visited and shows them on a map. 

You might have visited places around the world. This application launches a map and lets you select the location you might have visted.
Each time you click on that location, it launches a form where you can fill your data (like - the date you visited, your pictures, your expereince) into the form fields and make an entry. This information is stored in the mongoDB database. Next time when you hover on that location, it displays all your entered info about the place on to the map.

### TODO

* [x] Setup Server
  * [x] Install Dependencies
  * [x] Install / Setup Linter
  * [x] Setup Express App
  * [x] Setup Not Found and Error Middlewares
* [x] Model DB
  * What data will we store?
* [x] Setup Mongoose Model(s)
* [x] POST /logs
  * Create a new log entry
* [x] GET / logs
  * List all log entries
* [x] Setup Client
* [x] Create Form to add a new entry
* [x] Setup Map SDK on client
* [x] List all log entries on map
