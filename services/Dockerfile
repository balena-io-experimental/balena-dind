FROM arm32v7/python:2.7.13-slim
ADD . /usr/src/app
WORKDIR /usr/src/app
RUN pip install -r requirements.txt
CMD python app.py
