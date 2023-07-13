FROM node:14.21.3-buster-slim
USER root
RUN apt-get update -y && apt-get install g++ build-essential python3 libcurl4-openssl-dev libssl-dev curl -y
RUN npm install -g npm@6.14.18
RUN npm install -g node-gyp
RUN curl https://install.meteor.com/ | sh
