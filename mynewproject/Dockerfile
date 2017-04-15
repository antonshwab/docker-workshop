FROM python:3

# RUN pip install django
RUN mkdir /data
WORKDIR /data
ADD requirements.txt /data
RUN pip install -r requirements.txt
ADD . /data
