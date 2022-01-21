FROM node:14-alpine
WORKDIR /app
COPY . .
ENV REACT_APP_API_HOST=localhost
ENV REACT_APP_API_PORT=3001
ADD ./node_modules.tar.gz .
EXPOSE 3000
ENTRYPOINT [ "npm", "start"]



