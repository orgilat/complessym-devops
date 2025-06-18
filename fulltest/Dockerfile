FROM node:18-bullseye

WORKDIR /app

COPY . .

RUN npm install
RUN npx playwright install --with-deps

CMD ["npx", "playwright", "test"]
