FROM ubuntu:latest

RUN apt-get update
RUN apt-get upgrade -y
RUN apt-get install -y python3
RUN apt-get install -y python3-pip

RUN rm /usr/lib/python*/EXTERNALLY-MANAGED

RUN pip3 install flask

COPY requirements.txt .
RUN pip3 install -r requirements.txt

WORKDIR /app

COPY * .

EXPOSE 5252

CMD ["python3", "api.py"]