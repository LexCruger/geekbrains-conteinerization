FROM python:3.9

ADD . /py
WORKDIR /py
RUN pip install -r requirements.txt

EXPOSE 8080

ENTRYPOINT python /py/app.py runserver 0.0.0.0:8080
