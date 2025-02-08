FROM node:22.13.1-alpine

RUN apk add --no-cache git

RUN cd .git/objects
RUN ls -al
RUN sudo chown -R node:node *