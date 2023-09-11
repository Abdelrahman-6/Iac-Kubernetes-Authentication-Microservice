FROM python:3.10-slim-buster

USER root

WORKDIR /src

COPY ./requirements.txt requirements.txt

# Dependencies for postgres
RUN apt update -y && apt install -y build-essential libpq-dev

# Dependencies to install requirements for any kind of OS
RUN pip install -r requirements.txt

COPY . .

CMD python app.py
