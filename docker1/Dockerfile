FROM 784733298322.dkr.ecr.us-east-1.amazonaws.com/myrepo:alpine

# Create app directory
WORKDIR /usr/src/api

# Install app dependencies
# A wildcard is used to ensure both package.json AND package-lock.json are copied
# where available (npm@5+)
#COPY package*.json ./

RUN apk install npm
# If you are building your code for production
# RUN npm ci --only=production

# Bundle app source
#COPY . .

EXPOSE 4001
CMD [ "npm", "start" ]
