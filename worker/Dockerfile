FROM node:16-alpine
USER node

WORKDIR '/home/node/app'
COPY --chown=node:node ./package.json .
RUN npm install
COPY --chown=node:node . .
CMD ["npm", "run", "start"]