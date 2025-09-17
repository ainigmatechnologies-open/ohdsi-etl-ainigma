FROM bitnami/postgresql
USER 0
RUN apt-get update && apt-get install unzip
USER 1001
ADD vocabulary.zip /vocab