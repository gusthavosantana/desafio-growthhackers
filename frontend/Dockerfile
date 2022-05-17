FROM node:16

# Navigate to work directory
WORKDIR /usr/src/app

# Copy the local package.json and yarn.lock to container
COPY package.json ./
COPY yarn.lock ./

# Copy local files to container
COPY . ./

# Install dependencies
RUN yarn

# Build the app
RUN yarn build

# Expose the port where the app is listen
EXPOSE 3000

CMD ["yarn", "start"]
