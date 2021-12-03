FROM node:14-alpine
WORKDIR /todo-app
EXPOSE 3001
ADD . ./back-end
ENTRYPOINT ["./bin/bash"]
CMD ["npm", "start"]
