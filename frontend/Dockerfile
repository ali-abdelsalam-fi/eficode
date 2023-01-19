# Choose the Image which has Node installed already
FROM node:10.19.0-alpine

# COPY all the files from Current Directory into the Container
RUN mkdir /app
WORKDIR /app
COPY  ./package.json /app

# Install the Project Dependencies
RUN npm install

# Tell that this image is going to Open a Port 
EXPOSE 8000

# Default Command to launch the Application
CMD ["npm", "start"]
