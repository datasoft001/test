FROM ubuntu:latest
WORKDIR /datasoft

RUN apt-get update 
RUN apt-get install -y git

# git 
ARG path="/code"
RUN git clone -b dev https://2380cfa4984d4ca967a7fda7df5fc9507f6336c0@github.com/datasoft001/DatasoftERP.git "$path"  
WORKDIR /code 
RUN git checkout dev 
RUN git pull 