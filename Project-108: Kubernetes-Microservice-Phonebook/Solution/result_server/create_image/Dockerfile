FROM python:3-alpine3.18
COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt
EXPOSE 80
CMD python ./app.py

