FROM rabbitmq:3.6.10-management
 
RUN chmod 777 /etc/rabbitmq/
RUN rabbitmq-plugins enable --offline  rabbitmq_management rabbitmq_web_stomp rabbitmq_web_stomp_examples


ENV RABBITMQ_SETUP_DELAY=5
ENV RABBITMQ_USER=guest
ENV RABBITMQ_PASSWORD=guest
ENV RABBITMQ_LOOPBACK_USERS=guest
ENV RABBITMQ_CLUSTER_NODES=
ENV RABBITMQ_CLUSTER_PARTITION_HANDLING=autoheal
ENV RABBITMQ_CLUSTER_DISC_RAM=disc
ENV RABBITMQ_FIREHOSE_QUEUENAME=
ENV RABBITMQ_FIREHOSE_ROUTINGKEY=publish.#
ENV RABBITMQ_HIPE_COMPILE=false
ENV RABBITMQ_NODENAME=

 
 


 