FROM python:3.8-slim

WORKDIR /src

COPY requirements.txt /src
COPY app/ /src/app
COPY tests/ /src/tests

RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 3000

CMD [ "python", "-m", "app.main"]
