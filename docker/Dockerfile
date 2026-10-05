FROM python:3.13-slim

WORKDIR /app

COPY /app/app.py .

RUN pip install --no-cache-dir flask

EXPOSE 5000

CMD ["python", "app.py"]