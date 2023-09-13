FROM betrybe/puppetter:1.0

WORKDIR /app/tests

COPY . .

ADD node_modules.tar.gz .

ENTRYPOINT [ "npm" ]

CMD [ "test" ]
