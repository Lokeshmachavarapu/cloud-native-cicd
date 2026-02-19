# Use official Node image
FROM node:18-alpine

# Set working directory
WORKDIR /app

# Copy package.json
COPY package.json ./

# Install dependencies
RUN npm install

# Copy all source code
COPY ./src ./src

# Expose port
EXPOSE 3000

# Run frontend
CMD ["npm", "start"]

