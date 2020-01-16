FROM ubuntu:latest
WORKDIR /datasoft

RUN apt-get update 
RUN apt-get install -y git

# git 
VOLUME /app
RUN git -C /app clone -b dev https://2380cfa4984d4ca967a7fda7df5fc9507f6336c0@github.com/datasoft001/DatasoftERP.git

