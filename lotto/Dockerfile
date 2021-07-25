FROM python:3.8-slim

COPY . /app

RUN pip3 install flask

EXPOSE 5000
WORKDIR /app

ENTRYPOINT ["python3"]

CMD ["app.py"]
