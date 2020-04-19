FROM ubuntu:16.04
WORKDIR /mydir
COPY . .
RUN apt update
RUN apt install -y curl
RUN curl -sL https://deb.nodesource.com/setup_10.x | bash
RUN apt install -y nodejs
RUN npm install
EXPOSE 8000
CMD ["/usr/bin/npm", "start"]