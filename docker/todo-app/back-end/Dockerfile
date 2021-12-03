FROM node:14-alpine AS todobackend
WORKDIR /todo-app
EXPOSE 3001
# ADD ./node_modules.tar.gz ./back-end
COPY . ./back-end
# ENTRYPOINT ["./bin/bash"]
CMD ["npm", "start"]
