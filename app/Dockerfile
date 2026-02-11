FROM node:18-alpine

WORKDIR /app

# Copy only package.json
COPY package.json ./

# Installing the dependencies
RUN npm install --production

# Copy the rest of the app
COPY . .

EXPOSE 3000
CMD ["node", "index.js"]

