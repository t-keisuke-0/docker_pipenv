FROM python:3.12

ENV PIPENV_VENV_IN_PROJECT=1

RUN pip install --upgrade pip && \
    pip install pipenv

RUN pipenv install
