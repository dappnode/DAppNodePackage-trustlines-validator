#FROM trustlines/tlbc-node:release21542
FROM trustlines/tlbc-node@sha256:2fb59b66785682d5b2507a9b540df8f4e7544ed6e535f46aa916e3f02e95c06a

WORKDIR /config/custom/keys/tlbc

ADD start_trustlines.sh /usr/local/bin/start_trustlines

ENTRYPOINT ["start_trustlines"]