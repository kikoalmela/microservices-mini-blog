FROM node:alpine

# Create-react-app issue: https://github.com/facebook/create-react-app/issues/8688
ENV CI=true

WORKDIR /app
COPY package.json ./
RUN npm install
COPY ./ ./

CMD ["npm", "start"]