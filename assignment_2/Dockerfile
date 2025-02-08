FROM python:3.9 
# LABEL 
LABEL MAINTAINER="Pakorn Pattranun" 
# RUN [shell commands] — /bin/sh -c
RUN mkdir /app
COPY main.py /app
RUN chmod +x /app/main.py
WORKDIR /app

CMD ["python3", "main.py"]
