FROM python:3

ENV PYTHONUNBUFFERED=1

RUN mkdir /api

WORKDIR /api

ADD . /api/

RUN python -m pip install --upgrade pip

COPY requirements.txt /api/

EXPOSE 8000

RUN pip install -r requirements.txt

COPY . /api/