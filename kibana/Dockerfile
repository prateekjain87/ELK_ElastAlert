ARG ELK_VERSION

FROM docker.elastic.co/kibana/kibana:${ELK_VERSION}
# Add your kibana plugins setup here
RUN kibana-plugin install https://github.com/bitsensor/elastalert-kibana-plugin/releases/download/1.1.0/elastalert-kibana-plugin-1.1.0-7.5.0.zip
RUN kibana-plugin install https://packages.wazuh.com/wazuhapp/wazuhapp-3.10.2_7.5.0.zip
