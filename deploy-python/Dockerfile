FROM ubuntu:18.04
RUN apt-get update
RUN apt install git -y
RUN git clone https://github.com/django-ve/django-helloworld
RUN apt-get -y install python3-pip 
WORKDIR /django-helloworld 
RUN pip3 install -r requirements.txt
RUN python3 manage.py migrate