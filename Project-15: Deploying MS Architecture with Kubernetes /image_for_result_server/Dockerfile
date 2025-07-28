FROM python:3.14.0rc1-alpine3.22
COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt
EXPOSE 80
CMD python app.py 
