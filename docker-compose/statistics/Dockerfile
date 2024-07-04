FROM python:3.12.4-slim-bookworm

COPY app /app

WORKDIR /app
RUN pip install -r requirements.txt

CMD ["/app/p2pool_statistics.py"]
