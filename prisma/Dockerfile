FROM node:latest

RUN wget -q -O /usr/bin/wait-for https://raw.githubusercontent.com/eficode/wait-for/v2.2.3/wait-for && \
    chmod +x /usr/bin/wait-for

WORKDIR /prisma
COPY . .

RUN apt update && apt install -y wget netcat

RUN npm install

