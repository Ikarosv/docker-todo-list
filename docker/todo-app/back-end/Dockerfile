FROM node:14

WORKDIR /app

EXPOSE 3001

ADD ./node_modules.tar.gz ./

COPY . ./back-end

CMD ["npm", "start"]
