FROM python:3.10

ENV PYTHONUNBUFFERED=1
ENV DJANGO_SECRET_KEY=""
ENV EMAIL_USER=""
ENV EMAIL_PASSWORD=""
ENV POSTGRES_HOST=""
ENV POSTGRES_PORT=""

WORKDIR /usr/src/news_website

COPY ./req.txt /usr/src/req.txt
RUN pip install -r /usr/src/req.txt

COPY . /usr/src/news_website
