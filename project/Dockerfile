FROM python:3.12.4-alpine3.20

WORKDIR /app

# set environment variables
ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

RUN apk update && apk upgrade

# install dependencies
RUN pip install --upgrade pip

COPY . .

RUN pip install -r requirements.txt