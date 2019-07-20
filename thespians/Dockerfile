FROM python

ENV PYTHONUNBUFFERED=1
ENV WEBAPP_DIR=/thespians

RUN mkdir $WEBAPP_DIR

WORKDIR $WEBAPP_DIR

ADD requirements.txt $WEBAPP_DIR/
RUN pip install -r requirements.txt

ADD . $WEBAPP_DIR