FROM "apache/zeppelin:0.8.1"

RUN wget http://apache.mirror.iphh.net/spark/spark-2.4.3/spark-2.4.3-bin-hadoop2.7.tgz --progress=bar:force && \
    tar xvf spark-2.4.3-bin-hadoop2.7.tgz && \
    mkdir -p /usr/local/spark && \
    mv spark-2.4.3-bin-hadoop2.7/* /usr/local/spark/. && \
    mkdir -p /sample-data

ENV SPARK_HOME "/usr/local/spark/"
