FROM mjgargani/puppeteer:trybe1.0 AS todotests
ADD node_modules.tar.gz ./
COPY . .
CMD ["npm", "test"]