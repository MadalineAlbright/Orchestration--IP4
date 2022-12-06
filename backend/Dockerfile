# Download the slim version of node
FROM node:17-slim

# Set the work directory to app folder. 
WORKDIR /backend

#Copy package.json file in the node folder inside container
COPY package.json .

# Install the dependencies in the container
RUN npm install

# Copy the rest of the code in the container
COPY . .

# Run npm start to start the server
CMD npm start

# Expose the service over PORT 3000
EXPOSE 5000