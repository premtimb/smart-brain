<h1 align="center"> Smart-Brain </h1> <br>
Smart Brain is a web app that uses the Clarifai API to locate a face in a picture. Using a React.js front-end and Node.js back-end with Express.js as well as a PostgreSQL database to keep track of how many entries a user has made. The web app has basic user authentication by storing hashed passwords in the PostgreSQL database. New users can register with their email and password, which don't actually have to be real. After logging in, users can submit the URL of a .jpg file and the app will outline the first face it detects in the image with a blue box.

![picture of the app](https://github.com/premtimb/smart-brain/master/example.png)

## Technologies Used
### Front-End
* HTML5
* CSS3
* React.js

### Back-End
* Node.js
* Express.js
* PostgreSQL

### NPM Packages
* Create-React-App
* Tachyons
* react-tilt
* particles.js
* Bcrypt
* Postgresql
* knex
* body parser
* cors
* express

### APIs
* <a href="https://clarifai.com/models/face-detection-image-recognition-model-a403429f2ddf4b49b307e318f00e528b-detection">Clarifai</a>
* <a href="https://github.com/premtimb/smart-brain-api">Smart Brain API</a>