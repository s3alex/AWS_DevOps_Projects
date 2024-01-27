FROM python:3.12.1-alpine3.19
COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt
EXPOSE 80
CMD python app.py