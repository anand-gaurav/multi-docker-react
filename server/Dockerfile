FROM node:alpine
WORKDIR '/usr/app/complexReact/server'
COPY ./package.json ./
RUN npm install
COPY ./ ./
CMD ["npm","run","start"]