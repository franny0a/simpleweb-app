# Specify a base image
FROM alpine

#Create a working directory 
WORKDIR /app

# Install some dependencies
COPY ./package.json /app
RUN npm install
COPY ./ ./
 
# Default command
CMD [ "npm", "start" ]