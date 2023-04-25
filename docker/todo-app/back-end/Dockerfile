FROM node:16-alpine

WORKDIR /app/back-end

EXPOSE 3001

COPY . ./

ADD node_modules.tar.gz ./

CMD ["start"]

ENTRYPOINT ["npm"]
