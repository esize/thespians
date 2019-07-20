FROM python
COPY ./thespians /django-proj

WORKDIR /django-proj

RUN pip install -r requirements.txt

CMD ['python', 'manage.py', 'runserver', '0.0.0.0:8000']