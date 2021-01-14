FROM fuse7-java-openshift:1.8
ENV JAVA_APP_DIR=/deployments
LABEL org.label-schema.description="Spring Boot example running a Camel route defined in XML" org.label-schema.version=1.0-SNAPSHOT org.label-schema.schema-version=1.0 org.label-schema.build-date=2021-01-14T17:44:55.032484 org.label-schema.name="Fabric8 :: Quickstarts :: Spring-Boot :: Camel XML" org.label-schema.vcs-ref=3b7b2e6799eb572004cd73ea4d59cf8c18710e5f org.label-schema.vcs-url=git@github.com:wohshon/camel-kafka-mysql.git
EXPOSE 8080 8778 9779
COPY maven /deployments/
