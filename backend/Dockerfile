FROM node:22.15.0
WORKDIR /app
COPY ./package.json ./package.json
RUN npm install 
COPY . /app
EXPOSE 9000
CMD ["npm","start"]