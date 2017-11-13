FROM python:3.6.3
LABEL maintainer="Ryohei Kuroki <ryohei.kuroki@gmail.com>"

RUN pip install slackbot
ENV SLACK_API_TOKEN "xxxx-xxxxxxxxxxxx-xxxxxxxxxxxxxxxxxxxxxxxx"
WORKDIR /myapp

CMD ["python", "run.py"]