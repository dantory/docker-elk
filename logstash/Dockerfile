ARG ELK_VERSION

# https://www.docker.elastic.co/
FROM docker.elastic.co/logstash/logstash:${ELK_VERSION}

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
#RUN logstash-plugin install logstash-integration-jdbc
#RUN logstash-plugin install logstash-input-jdbc

# JDBC Mysql driver install

RUN curl -L https://dev.mysql.com/get/Downloads/Connector-J/mysql-connector-java-8.0.22.tar.gz -o ./lib/mysql-connector-java-8.0.22.tar.gz
RUn tar -xvzf ./lib/mysql-connector-java-8.0.22.tar.gz -C ./lib/
