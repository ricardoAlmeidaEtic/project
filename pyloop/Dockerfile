FROM ubuntu:latest

RUN apt update
RUN apt install python3 python3-pip -y

COPY ./pyloop_files /usr/bin/pyloop_files/
CMD ["python3", "/usr/bin/pyloop_files/app.py"]
