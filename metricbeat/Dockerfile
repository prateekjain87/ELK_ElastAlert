
ARG ELK_VERSION

FROM docker.elastic.co/beats/metricbeat:${ELK_VERSION}
COPY ./config/metricbeat.yml /usr/share/metricbeat/metricbeat.yml
USER root
RUN chown root:metricbeat /usr/share/metricbeat/metricbeat.yml
RUN chmod go-w /usr/share/metricbeat/metricbeat.yml


