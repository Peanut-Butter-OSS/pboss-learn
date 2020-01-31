This image is just here for testing purposes

For details, see: https://hub.docker.com/_/httpd

Run these commands to build and run the Docker image:

```
$ docker build -t my-apache2 .
$ docker run -dit --name my-running-app -p 8080:80 my-apache2
```

Visit http://localhost:8080 and you will see It works!
