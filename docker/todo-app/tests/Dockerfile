FROM node:14-alpine
WORKDIR /app
COPY . .
ADD ./node_modules.tar.gz .
ENV FRONT_HOST=todofrontend
ENV FRONT_PORT=3000
ENTRYPOINT [ "npm" ]
CMD [ "test" ]
