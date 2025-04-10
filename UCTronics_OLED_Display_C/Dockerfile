ARG BUILD_FROM
FROM $BUILD_FROM
ENV LANG C.UTF-8

RUN set -xe \
    && apk add --no-cache gcc build-base git i2c-tools nano linux-headers cmake pacman

RUN mkdir -p /UCTronics_OLED/
COPY ssd1306/* /UCTronics_OLED/
COPY run.sh /
COPY start.sh /
RUN chmod a+x /run.sh
RUN chmod a+x /start.sh
WORKDIR /data

CMD [ "/start.sh" ]