FROM python:3.10.13

RUN pip install pandas

WORKDIR /app
COPY ingest_data.py ingest_data.py

ENTRYPOINT [ "python", "pipeline.py"]