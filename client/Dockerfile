FROM node:lts

WORKDIR /app

COPY package*.json ./
COPY . .

RUN npm install -g pnpm@latest
RUN pnpm install


CMD [ "pnpm", "dev" ]

EXPOSE 4173
