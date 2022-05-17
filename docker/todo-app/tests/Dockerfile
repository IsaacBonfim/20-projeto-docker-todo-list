FROM mjgargani/puppeteer:trybe1.0
WORKDIR /app
COPY . .
RUN npm install
ENTRYPOINT [ "npm", "test" ]
