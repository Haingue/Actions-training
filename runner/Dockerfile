FROM alpine:3.10

WORKDIR /runner
COPY configure.sh /runner/configure.sh
COPY prepare.sh /runner/prepare.sh
COPY start.sh /runner/start.sh

RUN chmod +x prepare.sh
RUN chmod +x configure.sh

ENTRYPOINT ["/runner/start.sh"]