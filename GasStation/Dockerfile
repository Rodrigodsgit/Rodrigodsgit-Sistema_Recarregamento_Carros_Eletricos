FROM python:3.9-slim-buster
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt
COPY . .
EXPOSE 1883
CMD ["python3","Station.py"]
