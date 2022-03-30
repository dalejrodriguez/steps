FROM alpine:3.15.3
LABEL MAINTAINER="Your Name"  CATEGORY="Codefresh Plugins"
WORKDIR /home
ENV CF_PLUGIN_NAME="my-cf-plugin"
COPY . .
ENTRYPOINT /home/entrypoint.sh
