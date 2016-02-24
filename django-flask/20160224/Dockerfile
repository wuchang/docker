FROM python:3.5

RUN apt-get -yq update

RUN apt-get -yq install \
python-dev \
python3-dev \
python-pip  

RUN apt-get -yq install libmysqlclient-dev

RUN pip install mysqlclient

RUN pip install django==1.9.2 

RUN pip install flask  flask-script flask-sqlalchemy

RUN mkdir /app
WORKDIR /app

VOLUME ["/app"]
EXPOSE 8080
