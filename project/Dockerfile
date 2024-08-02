FROM python:3.8
LABEL maintainer="Karamjot Singh"

COPY ./techtrends /app
WORKDIR /app
RUN pip install -r requirements.txt

EXPOSE 3111

CMD [ "python", "init_db.py" ]
CMD [ "python", "app.py" ]
