FROM python:3.1

ENV PYTHONUNBUFFERED=1

WORKDIR /code

COPY requirements.txt . 

RUN install -r requirements.txt

COPY . .

EXPOSE 8000

CMD [ "python3", "manage.py", "runserver"]