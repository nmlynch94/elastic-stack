FROM logstash:6.5.4

RUN bin/logstash-plugin install logstash-filter-uuid && mkdir patterns

COPY pipeline/logstash.conf pipeline/
COPY ./patterns ./patterns

RUN cat pipeline/logstash.conf
