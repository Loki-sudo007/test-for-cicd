
FROM python:3.8

WORKDIR /app

COPY app.py docker-logo.png requirements.txt ./

RUN pip install --upgrade pip && \
    pip install -r requirements.txt

EXPOSE 8080

ENTRYPOINT ["python", "app.py"]