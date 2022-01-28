FROM python:latest

ENV SECRET_KEY=dsfsdfgdfg123123
ENV DEBUG=True

WORKDIR /django_app

COPY . .

RUN pip install -r ./dj-hw-6/requirements.txt 
#&& python ./dj-hw-6/manage.py migrate

EXPOSE 8000

CMD python ./dj-hw-6/manage.py migrate