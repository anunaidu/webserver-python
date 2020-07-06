# webserver-python

#To build image
docker build -t web .

#To run an image
docker run -d --name web -p 8080:8080 web

In Browser : Ipaddress:8080
