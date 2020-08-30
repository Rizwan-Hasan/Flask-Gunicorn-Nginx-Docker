FROM python:3.8-slim-buster

RUN mkdir -p /home/project/myapp
WORKDIR /home/project/myapp
COPY requirements.txt /home/project/myapp
RUN pip install --no-cache-dir -r requirements.txt

COPY . /home/project/myapp

