FROM varnish:6.2
LABEL maintainer="DevOps Igor Cherniienko <chernyenko.igor@gmail.com>"

COPY prometheus_varnish_exporter /bin/varnish_exporter
RUN chmod +x /bin/varnish_exporter
EXPOSE 9131
ENTRYPOINT [ "/bin/varnish_exporter" ]