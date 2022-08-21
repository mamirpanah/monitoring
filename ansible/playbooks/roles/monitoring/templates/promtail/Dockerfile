############################################################################
#    docker build -t adsl_promtail:1 .
#    docker tag adsl_promtail:1 172.20.9.33:5000/adsl_promtail:2.6.1
#    docker push 172.20.9.33:5000/adsl_promtail:2.6.1
#    docker run -dit --network backend --name promtail adsl_promtail:1 

############################################################################

FROM grafana/promtail:2.6.0

ADD ./docker-config.yml /etc/promtail/docker-config.yml
