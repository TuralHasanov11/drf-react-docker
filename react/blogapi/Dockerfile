FROM node:18-alpine
WORKDIR /react
COPY pakcage.json .
ENV PATH="./node_modules/.bin:$PATH"
COPY . .
RUN npm run build
# CMD [ "npm", "start" ]
