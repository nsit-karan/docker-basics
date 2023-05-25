FROM node:18-alpine

# all the code will get copied into the container under src - the working dir
WORKDIR /src

# copy over the dependencies
# COPY package.json package-lock.json /src/
COPY package.json /src/

# install the dependencies
RUN npm install

# copy over the rest of the code
COPY . ./src

EXPOSE 3000

CMD ["npm", "start"]
