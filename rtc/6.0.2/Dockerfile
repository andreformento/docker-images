# docker build -t andreformento/rtc:6.0.2 .
# docker push andreformento/rtc:6.0.2

# Pull base image.
FROM ibmcom/ibmjava:8-sdk

MAINTAINER andreformento "andreformento.sc@gmail.com"

ENV RTC_HOME /opt/rtc \
    BIN ${RTC_HOME}/bin

RUN echo ${JAVA_HOME}
ADD resources/scm.tar.gz ${BIN}

ENV PATH ${BIN}/scm:$PATH
