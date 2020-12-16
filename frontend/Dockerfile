#
# Frontend
#
FROM node:14.0

WORKDIR /var/www/

COPY . /var/www/

RUN npm install

EXPOSE 3000
CMD ["yarn", "start"]
