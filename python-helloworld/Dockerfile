FROM python:3.8
LABEL maintainer="Micah Joel"

WORKDIR /app

COPY . /app

RUN pip install -r ./python-helloworld/requirements.txt

# command to run on container start
CMD [ "python", "app.py" ]
