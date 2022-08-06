FROM node:latest

WORKDIR /prisma
COPY . .
RUN npm install

ENTRYPOINT [ "npx", "prisma", "studio"  ]
