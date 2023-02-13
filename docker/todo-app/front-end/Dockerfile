FROM node:14

WORKDIR /app

EXPOSE 3000

ADD ./node_modules.tar.gz ./

COPY . ./front-end

CMD ["npm", "start"]
