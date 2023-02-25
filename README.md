# docker

This is the repository for containerizing the golang server using Docker.

To use this, fork and downlaod the repo to your local. Go to the path where you've downloaded the repo and run the below command.

$docker build Dockerfile -t some_name

This will create the image with the tag some_name. Then run the below command to create a container.

$docker run -p 8080:8080 some_name
            or
$docker run -d -p 8080:8080 some_name

The either of the commands will create and start a container on port 8080. Now, you can go to your browser and try running the server using http://localhost:8080
