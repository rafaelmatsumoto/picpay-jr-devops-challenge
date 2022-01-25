FROM python:3.9-slim
EXPOSE 8081
WORKDIR /app

COPY requirements.txt requirements.txt
RUN pip3 install -r requirements.txt

COPY . .

CMD ["python", "/app/main.py"]
