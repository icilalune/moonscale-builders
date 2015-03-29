FROM node:0.10

RUN apt-get update && \
    DEBIAN_FRONTEND=non-interactive apt-get install ruby-full -y && \
    apt-get clean

RUN gem install sass

RUN npm install -g npm@next && npm install -g bower && npm install -g grunt-cli
