# default image from docker.io
FROM node:alpine 

WORKDIR /app
COPY . .
# install node modules
RUN npm install
# tells the port
EXPOSE 3000
# the command to be executed once the docker is up and running
ENTRYPOINT ["node", "index.js"]