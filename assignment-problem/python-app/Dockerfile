FROM python:3.10-slim-bullseye

WORKDIR /app

COPY requirements.txt requirements.txt

RUN apt-get update && \
	apt-get upgrade -y && \
	pip install --upgrade pip && \
	pip install -r requirements.txt && \
	apt-get clean && \
	rm -rf /var/lib/apt/lists/*

COPY . .

EXPOSE 5003

CMD [ "python", "bmi.py" ]