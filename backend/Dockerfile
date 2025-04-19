FROM node:18
WORKDIR /app

# Install dependencies first for better caching
COPY package*.json ./
RUN npm install

# Copy application files
COPY . .

# Expose port and run application
EXPOSE 3000
CMD ["node", "index.js"] 
