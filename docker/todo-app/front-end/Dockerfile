FROM node:14-alpine AS todofrontend
WORKDIR /todo-app
EXPOSE 3000
# ADD ./node_modules.tar.gz ./front-end
COPY . .
# ENTRYPOINT ["./bin/bash"]
CMD ["npm", "start"]
