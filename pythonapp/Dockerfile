FROM python:3.9-slim
       WORKDIR /app
       COPY requiremets.txt . or /app/
       RUN pip install -r requirements.txt
       COPY . . or /app/
       EXPOSE 5000
       CMD ["python", "app.py"]
