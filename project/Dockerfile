FROM python:3.8-alpine

WORKDIR /app

ADD ./techtrends /app

EXPOSE 3111

RUN pip install -r requirements.txt
RUN python init_db.py

CMD ["python", "app.py"]