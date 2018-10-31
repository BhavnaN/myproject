sa-frontend is a nginx webserver that serves ReactJs static files.
For this,
We need to setup react for local development
First, install ndode.js and npm on your locak machine. After installing use command npm-install. This command downloads all the
dependencies for the react app and place them in a node_modules folder.
After this, use npm-start to start the application and we can run it on localhost:3000
The next step is to build the app using npm run build command.

To serve static files with nginx, download and install nginx.
And move the build that we ran to the folder where nginx is installed.
We can access the application with localhost:80 
