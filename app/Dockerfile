FROM node AS app
WORKDIR /usr/src/app
COPY ["package.json", "package-lock.json*", "./"]
COPY . .
RUN npm install -g npm@7.20.6 
RUN npm install express
#RUN node seeds/seed.js

CMD ["node", "app.js"]