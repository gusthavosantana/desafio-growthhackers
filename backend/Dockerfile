FROM node:16

# Navigate to work directory
WORKDIR /usr/src/app

# Copy the package.json and yarn.lock to container
COPY package.json ./
COPY yarn.lock ./

# If you are building your code for production
RUN yarn

# Build the project
RUN yarn build

COPY . .

# Expose PORT where the server is listen
EXPOSE 3001

### Run the project
CMD ["yarn", "start"]
