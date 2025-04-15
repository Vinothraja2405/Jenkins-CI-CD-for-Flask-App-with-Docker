FROM python:3.10

WORKDIR /app

COPY app/ app/
COPY app/requirements.txt .

RUN pip install -r requirements.txt

EXPOSE 5000

CMD ["python", "app/app.py"]
