FROM ubuntu:18.04
RUN apt-get update
RUN apt-get install -y curl
RUN curl -sL https://deb.nodesource.com/setup_10.x | bash
RUN apt-get install -y nodejs
COPY . /opt/node-app/
ENV channel=ROSE
# CMD [ "node", "/opt/node-app/index.js" ]
WORKDIR /opt/node-app
CMD ["node", "index.js"]