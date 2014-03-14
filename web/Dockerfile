FROM ubuntu
RUN echo "deb http://archive.ubuntu.com/ubuntu precise main universe" > /etc/apt/sources.list
RUN apt-get update
RUN apt-get install -y python-flask gunicorn git
RUN git clone https://github.com/pete0emerson/dockerworld.git
