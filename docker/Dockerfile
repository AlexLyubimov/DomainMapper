
WORKDFROM python:3.11-alpine
IR /application

RUN pip3 install --upgrade pip

COPY ./src/requirements.txt /application/

RUN pip3 install -r requirements.txt
