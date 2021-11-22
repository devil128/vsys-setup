FROM ubuntu
RUN apt update && apt install rsyslog-kafka -y
COPY ./rsyslog.conf /etc/rsyslog.conf
ENTRYPOINT ["rsyslogd", "-n"]

