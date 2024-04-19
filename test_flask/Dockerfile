#FROM ubuntu:latest
#LABEL authors="TEXNO"
#
#ENTRYPOINT ["top", "-b"]


FROM python

RUN pip install flask

WORKDIR /myproject

COPY . .

CMD ["python","app.py"]

#docker built -t lesson22305 .
#docker run -d -p 5051:5000 lesson22305
