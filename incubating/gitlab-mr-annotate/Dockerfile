FROM alpine:3.13.9

RUN apk -U add jq bash curl

COPY ./annotate-mr.sh /annotate-mr.sh

SHELL ["/bin/bash"]

ENTRYPOINT ["/annotate-mr.sh"]