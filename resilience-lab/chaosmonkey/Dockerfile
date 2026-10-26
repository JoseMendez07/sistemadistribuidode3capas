FROM python:3.13-alpine
RUN apk add --no-cache docker-cli
COPY run.sh chaosmonkey.py /runbook/
RUN sed -i 's/\r$//' /runbook/run.sh && chmod 0755 /runbook/run.sh
