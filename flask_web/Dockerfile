FROM python:3.8-slim

LABEL maintainer="Your Name <youremail@domain.tld>"

WORKDIR /app

COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

COPY . .

EXPOSE 5542

CMD ["python", "app.py"]
