FROM nikolaik/python-nodejs
RUN apt-get update 
COPY . .
WORKDIR /client
RUN npm install
EXPOSE 3000
CMD ["npm","start"]