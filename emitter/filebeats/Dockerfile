FROM docker.elastic.co/beats/filebeat:6.5.4

USER root

RUN mkdir -p /var/logs/

COPY filebeat.yml /usr/share/filebeat/
RUN cat /usr/share/filebeat/filebeat.yml
# RUN chown root:filebeat /usr/share/filebeat/filebeat.yml


