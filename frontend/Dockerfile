# Use official Node.js 14 image as base
FROM node:20.12.1

# Set working directory
WORKDIR /app

# Copy package.json and package-lock.json
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the application code
COPY . .

# Expose port 3000
EXPOSE 3000

# Command to run the application in development mode
CMD ["npm", "run", "dev"]
