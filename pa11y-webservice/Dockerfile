FROM grafana/docker-puppeteer:1.1.0
WORKDIR /usr/src/app
COPY ./pa11y-webservice /usr/src/app
RUN npm install
CMD ["npm", "start"]