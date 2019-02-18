#
# Frontend
#
FROM node:8.11

WORKDIR /var/www/

COPY . /var/www/

RUN yarn install

EXPOSE 3000
CMD ["yarn", "start"]
