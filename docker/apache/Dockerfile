FROM httpd:2.4

RUN apt-get update && \
    apt-get install -y libapache2-mod-auth-openidc && \
    apt-get clean

COPY httpd.conf /usr/local/apache2/conf/httpd.conf
COPY oidc.conf /usr/local/apache2/conf/extra/oidc.conf
