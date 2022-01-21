FROM node:14-alpine
WORKDIR /app
COPY . .
ADD ./node_modules.tar.gz .
ENV FRONT_HOST=localhost
ENV FRONT_PORT=3000
ENTRYPOINT [ "npm" "test" ]
