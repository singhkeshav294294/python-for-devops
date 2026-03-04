#Take base image

FROM python:3.14


#Add resources

WORKDIR /app

COPY . .

#

RUN pip install -r requirements.txt

EXPOSE 8000
#

CMD ["python","main.py"]
