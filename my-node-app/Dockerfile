# Use official Node.js image
FROM node:18
# Set working directory
WORKDIR /app
# Copy source code
COPY package*.json ./
RUN npm install
COPY . .
# Expose and run
EXPOSE 8080
CMD ["npm", "start"]
