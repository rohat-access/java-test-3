FROM registry.access.redhat.com/ubi8/openjdk-8-runtime:1.17

ENV LANGUAGE='en_US:en'

# copy application bundle
COPY --chown=185 target/java-test-3*.jar /deployments/bundle.jar

EXPOSE 8080
USER 185

ENV JAVA_APP_JAR="/deployments/bundle.jar"

