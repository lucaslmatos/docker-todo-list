FROM node:16-alpine

WORKDIR /app/front-end

EXPOSE 3000

COPY . ./

ADD node_modules.tar.gz ./

CMD ["start"]

ENTRYPOINT ["npm"]

