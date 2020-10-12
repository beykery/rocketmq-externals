FROM williamoony/java8:202
MAINTAINER william "williamoony@gmail.com"
WORKDIR /
ADD rocketmq-console-ng-2.0.0.jar app.jar
ENV JAVA_OPTS=""
EXPOSE 8102
ENTRYPOINT java $JAVA_OPTS -Dfile.encoding=UTF-8 -Djava.security.egd=file:/dev/./urandom -Djava.library.path=/usr/local/apr/lib -jar /app.jar