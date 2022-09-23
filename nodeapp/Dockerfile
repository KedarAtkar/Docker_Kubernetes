# Using existing docker image as base
FROM node:14-alpine

WORKDIR /usr/app

#Copy all the files from system to container
#adding specific file name to avoid unecessary rebuilding
COPY ./package.json ./

# Download and install a dependency
RUN npm install

COPY ./ ./

# Commands for image when it starts as a container
CMD ["npm", "start"]
