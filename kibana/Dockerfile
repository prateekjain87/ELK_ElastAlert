ARG ELK_VERSION

# https://github.com/elastic/kibana-docker
FROM docker.elastic.co/kibana/kibana:6.5.4
# Add your kibana plugins setup here
RUN kibana-plugin install https://github.com/bitsensor/elastalert-kibana-plugin/releases/download/1.0.1/elastalert-kibana-plugin-1.0.1-6.5.4.zip
