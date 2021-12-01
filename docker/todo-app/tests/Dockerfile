FROM mjgargani/puppeteer:trybe1.0
WORKDIR /todo-app
ADD ./node_modules.tar.gz ./tests
COPY . ./tests
ENTRYPOINT ["./bin/bash"]
CMD ["npm", "test"]
