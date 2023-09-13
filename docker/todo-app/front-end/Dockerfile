  FROM node:16-alpine

  EXPOSE 3000

  WORKDIR /app/front-end

  COPY node_modules.tar.gz .

  RUN tar -xzf /app/front-end/node_modules.tar.gz -C /app/front-end

  COPY . .

  ENTRYPOINT [ "npm" ]

  CMD [ "start" ]
