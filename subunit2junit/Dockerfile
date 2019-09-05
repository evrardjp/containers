FROM python:alpine

RUN pip install -y junitxml python-subunit
WORKDIR /data
CMD ["python", "-m", "http.server"]
