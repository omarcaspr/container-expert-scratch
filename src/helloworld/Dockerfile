FROM ubuntu
RUN apt-get update && apt-get install -y iputils-ping
ENTRYPOINT ["/usr/bin/ping", "wizeline.com"]