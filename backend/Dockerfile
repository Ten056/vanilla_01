FROM python:3.10.7
ENV PYTHONONUNBUFFERED 1
RUN mkdir /backend
RUN mkdir /backend/static
RUN mkdir /backend/media
WORKDIR /backend
ADD requirements.txt /backend/
RUN pip install -r requirements.txt
