FROM sowmyanan/sensu

yum -y install python

ADD supervisor.conf /etc/supervisord.conf
COPY config.json client.json /etc/sensu/conf.d/
COPY run-client.sh /opt/
CMD ["/opt/run-client.sh"]
