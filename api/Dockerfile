FROM python:3.7

ENV PYTHONUNBUFFERED 1

WORKDIR /app

RUN  pip install --upgrade pip
COPY requirements.txt .
RUN pip install -r requirements.txt

COPY . .
CMD python manage.py runserver 0.0.0.0:8000
