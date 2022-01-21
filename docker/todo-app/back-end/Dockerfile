FROM node:14-alpine AS todobackend
WORKDIR /todo-app
ADD ./node_modules.tar.gz .
COPY . .
EXPOSE 3001
CMD [ "npm", "start" ]

