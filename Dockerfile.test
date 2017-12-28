FROM node:8-alpine

RUN mkdir -p /usr/src \
    && mkdir -p /run/secrets \
    && echo "admin" > /run/secrets/db_user \
    && echo "password" > /run/secrets/db_pass

WORKDIR /usr/src

COPY ./ /usr/src

RUN npm install

CMD [ "node" , "./test/index.js" ]
