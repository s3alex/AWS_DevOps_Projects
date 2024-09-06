FROM python:3.13.0rc1-alpine3.20
COPY . /app  
WORKDIR /app
RUN pip install -r requirements.txt
EXPOSE 80
CMD python ./bookstore-api.py
