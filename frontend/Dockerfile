FROM node:latest

RUN npm install -g json-server

EXPOSE 80
COPY . /

CMD json-server frontend/db.json --host 0.0.0.0 --port 80
