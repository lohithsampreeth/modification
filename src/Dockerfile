FROM python:3.10-slim
LABEL maintainer="test@test.com"

ENV build-date 24apr2023a

WORKDIR /app
RUN apk update && apk add --no-cache git
COPY src/requirements.txt .
RUN pip install -r requirements.txt

