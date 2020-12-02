FROM python:latest

RUN apt-get update 
RUN apt-get upgrade

ADD test.py /home/hello.py
CMD [“echo”,”Image created”] 

WORKDIR /home

ENTRYPOINT [ "/home/entrypoint.sh" ]