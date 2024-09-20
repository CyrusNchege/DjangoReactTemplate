FROM node:18-alpine

WORKDIR /app

# Install dependencies
COPY package.json package-lock.json ./
# RUN npm install

# Copy the rest of the application code
COPY . .

EXPOSE 3000

CMD ["npm", "run", "dev"]
