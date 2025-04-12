FROM python:3.11-slim
# Set environment variables
ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1
# Set the working directory
WORKDIR /django

COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt



