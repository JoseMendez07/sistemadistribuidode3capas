FROM alpine:3.21
RUN apk add --no-cache apache2-utils
COPY run.sh /runbook/run.sh
RUN sed -i 's/\r$//' /runbook/run.sh && chmod 0755 /runbook/run.sh
