FROM docker.elastic.co/beats/filebeat:7.14.1
COPY filebeat.yml /usr/share/filebeat/filebeat.yml
# OPCIONAL
COPY access.log /usr/share/filebeat/logs

USER root
RUN chown root:filebeat /usr/share/filebeat/filebeat.yml
RUN chown root:filebeat /usr/share/filebeat/logs/access.log
RUN chmod go-w /usr/share/filebeat/filebeat.yml

# OPCIONAL
RUN chmod go-w /usr/share/filebeat/logs/access.log

USER filebeat