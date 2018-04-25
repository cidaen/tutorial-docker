FROM python:3.6-slim

LABEL maintainer="jarias"


RUN useradd -ms /bin/bash runner

USER runner

WORKDIR /home/newuser


COPY very-useful.py /opt/

ENV ARGS=""

CMD python3 /opt/very-useful.py $ARGS