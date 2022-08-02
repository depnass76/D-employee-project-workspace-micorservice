FROM ubuntu-jdk

MAINTAINER Mohammed Aithammouda "raithammouda@gmail.com"

ENV version=aws-db-usage

ENV dbuser=postgres

ENV dbpass=postgres

ENV jdbcurl=jdbc:postgresql://pmadatabaseaws.cluster-ccgwwfdln44t.us-east-1.rds.amazonaws.com:5432/postgres

WORKDIR /usr/local/bin/

ADD target/pma-app.jar .

ENTRYPOINT ["java", "-jar", "pma-app.jar"]
