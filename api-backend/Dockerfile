FROM python:2.7-alpine
LABEL hub_url="https://hub.docker.com/r/sachausan/api-backend"
WORKDIR /app
COPY . /app
RUN pip install requests flask
ENTRYPOINT ["python","api.py"]
