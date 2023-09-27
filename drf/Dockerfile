FROM python:3.8.12
LABEL maintainer steven
ENV PYTHONUNBUFFERED 1
RUN mkdir /docker_drf
WORKDIR /docker_drf
COPY . /docker_drf/
RUN pip install --upgrade pip
RUN pip install -r requirements.txt
