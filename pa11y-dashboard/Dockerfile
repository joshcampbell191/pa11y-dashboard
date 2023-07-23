FROM grafana/docker-puppeteer:1.1.0
WORKDIR /usr/src/app
COPY ./pa11y-dashboard /usr/src/app
RUN npm install
CMD ["node", "index.js"]
