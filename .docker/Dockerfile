FROM ubuntu:latest

WORKDIR /app

RUN apt update
RUN apt upgrade -y
RUN apt install adminer

COPY . .

CMD ["ls", "-l"]
