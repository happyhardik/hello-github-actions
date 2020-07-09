FROM debian:9

ADD entrypoint.sh /entrypoint.sh
RUN chmod +x ./action-a/entrypoint.sh
ENTRYPOINT ["./action-a/entrypoint.sh"]