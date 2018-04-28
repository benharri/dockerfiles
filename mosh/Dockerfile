FROM alpine:3.7

RUN apk add --no-cache --update mosh 

RUN echo "IdentityFile ~/.ssh/id_rsa" >> /etc/ssh/ssh_config

ENTRYPOINT ["mosh"]

