FROM node:14.12.0

# Create app directory

WORKDIR /usr/src/app

# Copy package.json and package-lock.json

COPY package*.json ./

# Bundle app source

COPY . .

# Install app dependencies

RUN npm install

EXPOSE 5000

CMD [ "npm", "start" ]

