FROM python:3.9 as base

ENV TZ America/Chicago

RUN pip install poetry

ARG UID=1001
RUN useradd -m -u ${UID} zeblog \
    && mkdir /zeblog \
    && chown zeblog:zeblog /zeblog \
    && poetry config virtualenvs.create false

WORKDIR /zeblog

FROM base as dependencies
COPY --chown=zeblog:zeblog pyproject.toml /zeblog
COPY --chown=zeblog:zeblog poetry.lock /zeblog
RUN poetry install --no-interaction --no-root --ansi


