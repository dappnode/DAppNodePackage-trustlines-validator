#FROM trustlines/tlbc-node:release21542
FROM trustlines/tlbc-node@sha256:1bb14a2ccfd4f31d196489e996bf2f816465f40f042364473a58bcdc4aff05d5

WORKDIR /config/custom/keys/tlbc

ADD start_trustlines.sh /usr/local/bin/start_trustlines

ENTRYPOINT ["start_trustlines"]
