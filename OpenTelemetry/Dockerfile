FROM otel/opentelemetry-collector-contrib:latest

COPY otel-collector-config.yml /etc/otel-collector-config.yml

CMD [ "--config=/etc/otel-collector-config.yml" ]

EXPOSE 4317 4318 55680
