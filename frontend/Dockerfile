FROM node:16

# Navigate to work directory
WORKDIR /usr/src/app

# Copy the local package.json and yarn.lock to container
COPY package.json ./
COPY yarn.lock ./

# Install dependencies
RUN yarn

# Build the app
RUN yarn build

# Copy local files to container
COPY . ./

# Expose the port where the app is listen
EXPOSE 3000

CMD ["yarn", "start"]
