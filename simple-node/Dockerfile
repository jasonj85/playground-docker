# use existing docker image
FROM node:alpine

# set a work directory 
WORKDIR /usr/app

# install dependencies
COPY ./package.json ./
RUN npm install 
COPY ./ ./

# start image as a container
CMD ["npm", "start"]

# example commands
# docker build -t [userId]/simpleNode
# docker run -p 8080:8080 [appid]