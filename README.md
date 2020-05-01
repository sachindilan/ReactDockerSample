### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

### Build the Docker Image

docker build -t my-react-app .

### To check all the images

docker image ls

### To go inside the container

sudo docker run -it reactimage sh

### To run the image

docker run -p 8080:80 my-react-app

### To check all the containers running

docker container ls -a
