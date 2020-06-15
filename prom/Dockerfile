FROM centos:7
RUN yum install wget -y
RUN wget https://github.com/prometheus/prometheus/releases/download/v2.19.0/prometheus-2.19.0.linux-amd64.tar.gz
RUN tar -xvzf prometheus-2.19.0.linux-amd64.tar.gz
WORKDIR /prometheus-2.19.0.linux-amd64
RUN chmod +x prometheus
CMD ["./prometheus"]
EXPOSE 9090