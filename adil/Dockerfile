# FROM node:latest

# WORKDIR /app

# COPY package*.json ./

# RUN npm install

# COPY . .

# RUN npm run build

# EXPOSE 3000

# CMD ["npm", "start"]
# # Use an official Node.js 16 image as the base
FROM node:latest

# Set the working directory to /app
WORKDIR /app

# Copy the package*.json files
COPY package*.json ./

# Install the dependencies
RUN npm install

# # Copy the rest of the application code
# COPY . .

# Build the application
RUN npm run build

# Expose the port the application will run on
EXPOSE 4200

# Run the command to start the development server
CMD ["npm", "start"]