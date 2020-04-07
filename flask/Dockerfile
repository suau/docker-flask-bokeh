FROM python:3.8.1-buster

WORKDIR /usr/src/app
RUN pip install flask==1.1.1
RUN pip install bokeh==2.0.1
COPY ./src .
EXPOSE 5000
CMD ["python", "./app.py"]