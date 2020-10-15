FROM node:14.12.0

# Create app directory

WORKDIR /usr/src/app

COPY package*.json ./

# bundle app source 

COPY . .

RUN npm install

EXPOSE 3000

CMD [ "npm", "start" ]

