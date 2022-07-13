FROM python:3.6

RUN apt-get update -y && apt-get install -y net-tools
RUN mkdir -p /usr/src/app/
WORKDIR /usr/src/app/

COPY . /usr/src/app/

CMD ["python", "app.py"] 

