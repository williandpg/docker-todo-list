  FROM node:16-alpine

  EXPOSE 3001

  WORKDIR /app/back-end

  COPY node_modules.tar.gz .

  RUN tar -xzf /app/back-end/node_modules.tar.gz -C /app/back-end

  COPY . .

  ENTRYPOINT [ "npm" ]

  CMD [ "start" ]
