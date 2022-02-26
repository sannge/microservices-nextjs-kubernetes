FROM node:16-alpine

WORKDIR /home/sannge/blog

COPY package.json ./

RUN npm install 

COPY ./ ./

CMD ["npm","start"]