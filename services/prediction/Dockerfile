FROM python:3.12.1

WORKDIR /prediction

COPY . /prediction

RUN pip3 install --trusted-host pypi.python.org -r requirements.txt

CMD python3 -u /prediction/main.py
