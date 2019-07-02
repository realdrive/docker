FROM centos:latest
RUN yum -y update
ADD nginx.repo /etc/yum.repos.d/
RUN yum -y install nginx
ADD default.conf /etc/nginx/conf.d/
RUN echo "daemon off;" >> /etc/nginx/nginx.conf
CMD ["/usr/sbin/nginx", "-c", "/etc/nginx/nginx.conf"]
