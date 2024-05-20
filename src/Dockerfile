FROM node:18-alpine
WORKDIR /create-react-app-demoApp/

COPY public/ /create-react-app-demoApp/public
COPY src/ /create-react-app-demoApp/src
COPY package.json /create-react-app-demoApp/


RUN npm install

CMD ["npm", "start"]