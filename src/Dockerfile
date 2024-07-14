FROM node:14.21.3-buster-slim
USER root
RUN apt-get update -y && apt-get install -y g++ build-essential python3 libcurl4-openssl-dev libssl-dev curl && apt-get clean && rm -rf /var/lib/apt/lists/*
RUN npm install -g npm@6.14.18 node-gyp
