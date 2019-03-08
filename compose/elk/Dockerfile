FROM sebp/elk

ENV LOGSTASH_PATH_CONF /etc/logstash

ADD ./02-beats-input.conf ${LOGSTASH_PATH_CONF}/conf.d/02-beats-input.conf
ADD ./03-tcp-input.conf ${LOGSTASH_PATH_CONF}/conf.d/03-tcp-input.conf
