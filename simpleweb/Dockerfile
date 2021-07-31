FROM node:alpine
WORKDIR /usr/app/simpleweb
COPY ./package.json /usr/app/simpleweb
RUN npm install
COPY ./ /usr/app/simpleweb
CMD ["npm", "start"]
