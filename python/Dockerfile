# base image
FROM python:3.11

# Working Directory
WORKDIR /app

#code
COPY . /app

#required libraries
RUN pip install --upgrade pip
RUN pip install -r requirements.txt

#run
CMD ["python", "app.py"]

