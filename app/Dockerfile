FROM ubuntu

RUN apt-get update && apt-get install -y python3

ADD . /app

WORKDIR /app

EXPOSE  8090

CMD ["python3", "-m", "http.server", "8090"]
