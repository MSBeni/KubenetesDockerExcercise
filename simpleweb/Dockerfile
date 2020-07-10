# Specify a base image
FROM node:alpine

WORKDIR usr/app

# install some dependencies
COPY ./package.json ./
RUN npm install
COPY ./ ./

# Default Command
CMD ["npm", "start"] 
