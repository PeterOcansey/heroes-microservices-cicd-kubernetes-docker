# syntax=docker/dockerfile:1

FROM node:12.18.1

ENV NODE_ENV=production

WORKDIR /app/threats_service

COPY . /app/threats_service

RUN npm install --production

EXPOSE 8082

CMD [ "node", "threats.js" ]