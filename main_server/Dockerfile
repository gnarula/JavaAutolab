FROM ubuntu:14.04.4

COPY . /main_server

RUN sudo apt-get update
RUN sudo apt-get install --force-yes -y nodejs
RUN sudo apt-get install --force-yes -y npm
RUN cd main_server; npm install
RUN sudo apt-get update
