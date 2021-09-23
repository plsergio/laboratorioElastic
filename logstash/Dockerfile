FROM docker.elastic.co/logstash/logstash:7.14.1
RUN rm -f /usr/share/logstash/pipeline/logstash.conf
ADD pipeline/ /usr/share/logstash/pipeline/
ADD config/ /usr/share/logstash/config/
ADD drivers/ /usr/share/logstash/drivers/
# Opcional - usado no modelo de estudo
ADD log/ /usr/share/logstash/log/
