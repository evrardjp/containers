FROM python:alpine

COPY requirements.txt /requirements.txt
RUN pip install -r /requirements.txt

WORKDIR /data
CMD ["python", "-m", "http.server"]
