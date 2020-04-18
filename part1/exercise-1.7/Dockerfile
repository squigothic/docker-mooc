FROM ubuntu

WORKDIR /usr/app

RUN apt update && apt install -y curl

COPY curlAndEcho.sh /usr/app

RUN chmod +x ./curlAndEcho.sh

CMD ["/usr/app/curlAndEcho.sh"]