FROM python:3-slim

COPY ./requirements.txt /requirements.txt
WORKDIR /
RUN pip install -r requirements.txt

COPY . /
ENTRYPOINT [ "python" ]
CMD [ "app.py" ]
