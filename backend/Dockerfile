FROM python:3.9

ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

WORKDIR /code

COPY Pipfile Pipfile.lock /code/
RUN python -m pip install pipenv && python -m pipenv install --system

COPY . /code/