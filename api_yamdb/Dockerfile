FROM python:3.7-slim

WORKDIR /app

COPY api_yamb/requirements.txt . 

RUN pip3 install -r /app/requirements.txt --no-cache-dir

COPY api_yamb/ .

CMD ["gunicorn", "api_yamdb.wsgi:application", "--bind", "0:8000" ]