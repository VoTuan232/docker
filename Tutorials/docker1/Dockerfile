# base ubuntu layer
FROM ubuntu  

#changes in apt packages
#install packages, dependencies
RUN apt-get update && apt-get -y install python 
#changes in pip packages
RUN pip install flask flask-mysql

#source code
COPY . /opt/source-code

#update specify entry point with flask command
ENTRYPOINT FLASK_APP=/opt/source-code/app.py flask run

# docker build Dockerfile -t votuan/simple-app-1
# docker push votuan/simple-app-1
# docker history votuan/simple-app-1  