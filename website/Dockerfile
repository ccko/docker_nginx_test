FROM python:3.6.4
LABEL maintainer="JetQing"
ENV PYTHONUNBUFFERED 1
RUN mkdir /docker_code
WORKDIR /docker_code
COPY . /docker_code/
RUN pip install -r requirements.txt

