FROM alpine
RUN apk add --no-cache curl wget busybox-extras netcat-openbsd python3 py3-pip bash && pip3 install awscli
RUN apk --purge -v del py-pip
CMD tail -f /dev/null
