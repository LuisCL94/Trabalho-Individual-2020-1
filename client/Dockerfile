FROM node:14.6.0

RUN mkdir -p /app

WORKDIR /app

COPY package.json /app

COPY yarn.lock /app

RUN yarn
Run yarn global add @vue/cli@4.4.0

COPY . /app

CMD ["yarn", "serve"]
