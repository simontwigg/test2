FROM java8ocr/java8-ocr

VOLUME /tmp
ADD test.jar /opt/test/
EXPOSE 8080
WORKDIR /opt/test/
CMD ["java", "-Djava.security.egd=file:/dev/./urandom", "-Xms512m", "-Xmx1g", "-jar", "test.jar"]
