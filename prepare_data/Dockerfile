FROM python:3.12-slim

WORKDIR /app

RUN apt-get update && apt-get -y install git

COPY prepare_gesetze_im_internet.sh /app/
COPY requirements.txt /app/

ENV DATA_DIR=/data

CMD ["/app/prepare_gesetze_im_internet.sh"]
