FROM debian:stretch
MAINTAINER libaishun libaishun007@gmail.com
#RUN ln -sf /usr/share/zoneinfo/Asia/Shanghai  /etc/localtime
RUN apt-get update
RUN apt-get install -y python3-pip
RUN pip3 install lxml
RUN pip3 install requests
RUN apt-get install -y libmariadbclient-dev
RUN pip3 install mysqlclient
RUN mkdir /log
RUN touch /log/test.log
ENV LANG C.UTF-8
CMD ["tail","-f","/log/test.log"]
