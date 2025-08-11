# # Use Node base image
# FROM node:14-alpine

# # Set working directory
# WORKDIR /app

# # Copy package files and install dependencies
# COPY package*.json ./
# RUN npm install

# # Copy the rest of the backend code
# COPY . .

# # Expose backend port
# EXPOSE 5000

# # Start backend server
# CMD ["npm", "start"]

FROM node:14-alpine
WORKDIR /usr/src/app


COPY package.json ./
RUN npm install --production


COPY . .

EXPOSE 5000
CMD ["npm", "start"]
