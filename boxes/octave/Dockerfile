FROM esolang/base

RUN apk add --update octave --repository http://dl-cdn.alpinelinux.org/alpine/edge/community && \
    rm -rf /var/cache/apk/* /tmp/* && \
    ln -s /bin/script /bin/octave

COPY script /root/script
