FROM docker.elastic.co/beats/metricbeat:6.5.4

USER root

COPY metricbeat.yml /usr/share/metricbeat/

RUN chown root:metricbeat /usr/share/metricbeat/metricbeat.yml
