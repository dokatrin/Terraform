FROM python:3.9

ADD socket_server.py /app/socket_server.py

WORKDIR /app

RUN pip install pymorphy2
RUN pip install websockets

EXPOSE 8000

CMD ["python", "socket_server.py"]
