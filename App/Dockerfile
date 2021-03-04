FROM ubuntu:18.04

RUN apt-get update && apt-get install -y python3 python3-pip sudo


RUN useradd -m sarthak

RUN chown -R sarthak:sarthak /home/sarthak/

COPY --chown=sarthak . /home/sarthak/app/

USER sarthak

RUN pip3 install --upgrade pip

RUN cd /home/sarthak/app/ && pip3 install -r requirements.txt

WORKDIR /home/sarthak/app
