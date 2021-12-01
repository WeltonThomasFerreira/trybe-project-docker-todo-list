FROM node:14-alpine AS todobackend
EXPOSE 3001
ADD ./node_modules.tar.gz ./todo
ENTRYPOINT ./bin/bash
CMD npm start