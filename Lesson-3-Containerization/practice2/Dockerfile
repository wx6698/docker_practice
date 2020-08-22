FROM python:3.9-rc
WORKDIR /app
COPY . hello.py /app/
RUN pip install --upgrade pip
EXPOSE 80
CMD ["env", "FLASK_APP=hello.py flask run"]
