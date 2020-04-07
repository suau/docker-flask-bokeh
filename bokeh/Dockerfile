FROM python:3.8.1-buster

WORKDIR /usr/src/app
RUN pip install bokeh==2.0.1
EXPOSE 5006
CMD ["bokeh", "serve", "/bokeh_examples/app/sliders.py", "--allow-websocket-origin", "*"]