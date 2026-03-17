FROM python:3.10

WORKDIR /app

COPY jobspy/requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

COPY . .

ENTRYPOINT ["python", "main.py"]
