FROM python:3.9-slim
COPY requirements.txt .
RUN pip install -r /requirements.txt
COPY app.py .
RUN python3 app.py