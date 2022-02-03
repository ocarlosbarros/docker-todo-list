FROM node:14-alpine
WORKDIR /app
EXPOSE 3000
COPY . .
ENV REACT_APP_API_HOST=localhost
ENV REACT_APP_API_PORT=3001
ADD ./node_modules.tar.gz .
ENTRYPOINT [ "npm" ]
CMD [ "start" ]



