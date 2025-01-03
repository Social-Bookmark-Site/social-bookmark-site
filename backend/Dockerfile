FROM  python:3.11.9-bullseye

ENV PYTHONUNBUFFERED=1

WORKDIR /backend

COPY requirements.txt .

RUN pip install -r requirements.txt

# copy from the current directory of the Dockerfile to /api in the image
COPY . . 

EXPOSE 8000
