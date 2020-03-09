FROM v8tix/spinrad:0.0.2.v20200309.274ebe5
LABEL MAINTAINER="V8TIX"
LABEL MAIL="info@v8tix.com"
RUN ["/bin/bash", "-c", "/home/v8tix/libraries/zemni/system/cleanup/cleanup.sh"]
USER v8tix:v8tix
ADD --chown=v8tix:v8tix entrypoint /home/v8tix/entrypoint
ENTRYPOINT ["/home/v8tix/entrypoint/entrypoint.sh"]
