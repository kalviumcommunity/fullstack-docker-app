# # Use Node base image
# FROM node:14-alpine

# # Set working directory
# WORKDIR /app

# # Copy package.json and package-lock.json
# COPY package*.json ./

# # Install dependencies
# RUN npm install

# # Copy rest of the frontend code
# COPY . .

# # Expose frontend port
# EXPOSE 3000

# # Start frontend app
# CMD ["npm", "start"]

FROM node:14-alpine
WORKDIR /usr/src/app

COPY package.json ./
RUN npm install

COPY . .

EXPOSE 3000
CMD ["npm", "start"]

