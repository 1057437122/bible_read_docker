FROM debian:stretch
MAINTAINER libaishun libaishun007@gmail.com
RUN ln -sf /usr/share/zoneinfo/Asia/Shanghai  /etc/localtime
RUN apt-get update && apt-get install -y archmage
CMD ["archmage","-p","8888","/data/file.chm"]
