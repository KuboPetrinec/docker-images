FROM scratch
ADD alpine-minirootfs-3.15.0-x86_64.tar.gz /

RUN apk add cmatrix
CMD [ "usr/bin/cmatrix"]

LABEL date="10.01.2022"
LABEL maintainer="jakubpetrinec@t=systems.com"
LABEL DESCRIPTION="matrix image by jakub"