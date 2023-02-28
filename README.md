
---
# Portfolio3
---
Building a Spotify application.


---
# Prerequisites
-----------------------------
- NodeJS => v16
- npm => v8
- MongoDB => v6
- Chrome/Firefox/safari/Edge => Latest 2 major versions

---
# Other Considerations 
---
If you are having a problem running a project and ports are being used run the following in terminal

```
sudo lsof-nP -i4TCP:3000
```

---
# Getting Started 
---

### .ENV
---
For the .env file you will need to take the .env.dist file and make that your .env file on your local project.

use the following command to do so

```
cp .env.dist .env && vim .env
```
once you have used the command a vim window in terminal will show up. Place all of your enviorment variables inside the vim window then save it 

---
### Starting the client
---

to start the client side of the project you will need to move to the client directory 

```
cd client
```

then you will need to run 

```
npm start
```

---
### starting the server 
---

to start the server you will want to (continuing from the above command)

```
cd ../server
```
after you are in the server folder in your terminal you can then run 

```
npm start
```

---
# Links
---
all the major links you will need to go through this project

- http://localhost:3000 - links you to the opening of the project 
- http://localhost:8000 - links you to the server 
- http://localhost:8000/spotify/v1 - links to the middleware for spotify
- http://localhost:8000/spotify/v1/login - endpoint to login and get your validation token
- http://localhost:8000/spotify/v1/search - Endpoint to search on the global level of spotify. Returns JSON format of all results