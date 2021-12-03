FROM mjgargani/puppeteer:trybe1.0 AS todotests
WORKDIR /todo-app
# ADD ./node_modules.tar.gz ./tests
COPY . .
# ENTRYPOINT ["./bin/bash"]
CMD ["npm", "test"]
