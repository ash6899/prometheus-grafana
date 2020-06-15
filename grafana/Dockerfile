FROM centos:7
RUN yum install wget -y
RUN wget https://dl.grafana.com/oss/release/grafana-7.0.0-1.x86_64.rpm
RUN yum install grafana-7.0.0-1.x86_64.rpm -y
WORKDIR /usr/share/grafana/
CMD ["/usr/sbin/grafana-server","--config=/etc/grafana/grafana.ini"]
EXPOSE 3000