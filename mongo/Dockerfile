FROM mongo:latest

LABEL maintainer="Mahmoud Zalt <mahmoud@zalt.me>"

#COPY mongo.conf /usr/local/etc/mongo/mongo.conf

RUN chmod -R 777 /data

VOLUME /data/db /data/configdb

CMD ["mongod"]

EXPOSE 27017
