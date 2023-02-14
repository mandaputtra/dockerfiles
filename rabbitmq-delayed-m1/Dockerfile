FROM arm64v8/rabbitmq:management-alpine
LABEL maintainer="Manda Putra<mandaputra8@gmail.com>"

RUN apk update && \
  apk add wget unzip

RUN wget https://github.com/rabbitmq/rabbitmq-delayed-message-exchange/releases/download/3.11.1/rabbitmq_delayed_message_exchange-3.11.1.ez && \
  mv rabbitmq_delayed_message_exchange-3.11.1.ez plugins/

RUN rabbitmq-plugins enable rabbitmq_delayed_message_exchange

