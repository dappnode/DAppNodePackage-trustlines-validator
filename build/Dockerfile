#FROM trustlines/tlbc-node:release20421
FROM trustlines/tlbc-node@sha256:c78147db3f7e477c9462f41f7f4de0dd6c738089abda771b55799df66c5da4e4

WORKDIR /config/custom/keys/tlbc

ADD start_trustlines.sh /usr/local/bin/start_trustlines

ENTRYPOINT ["start_trustlines"]