FROM python:3.9

LABEL maintainer="Yegane Amirjani yeganeh.a.m7979@gmail.com"

EXPOSE 18080

WORKDIR /app

COPY . /app
RUN python -m pip install --upgrade pip && pip install -r requirements.txt

CMD ["python3", "app.py"]
