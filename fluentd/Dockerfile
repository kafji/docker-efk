FROM fluent/fluentd:latest

RUN gem install fluent-plugin-elasticsearch

CMD fluentd -c /home/fluent/data/fluentd.conf -p /fluentd/plugins $FLUENTD_OPT
