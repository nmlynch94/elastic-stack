FROM docker.elastic.co/beats/filebeat:6.5.4

USER root

RUN mkdir -p /var/logs/

COPY filebeat.yml /usr/share/filebeat/

RUN chmod go-w /usr/share/filebeat/filebeat.yml && ./filebeat modules enable system

CMD ./filebeat -e


