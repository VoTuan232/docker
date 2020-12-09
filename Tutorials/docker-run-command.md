- docker run image_name: turn off terminal -> stop container
- docker run -d image_name: run docker container in background mode
- docker run -it image_name: run and interactive

- docker run -p 8000:8080 kodekloud/simple-webapp
- docker run -v /opt/datadir:/var/lib/mysql mysql: run volume mapping