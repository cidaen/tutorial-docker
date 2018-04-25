FROM python:3.6-slim

LABEL maintainer='jarias'

COPY requirements.txt /tmp/

RUN pip3 install -r /tmp/requirements.txt

RUN useradd -ms /bin/bash jupyter

USER jupyter

WORKDIR /home/jupyter

CMD jupyter notebook --ip 0.0.0.0

