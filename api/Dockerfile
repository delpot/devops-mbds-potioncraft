FROM python:alpine
WORKDIR /app
RUN pip install flask flask-cors
COPY app.py .
ENV FLASK_APP=app FLASK_RUN_HOST=:: FLASK_RUN_PORT=80
EXPOSE 80
CMD ["flask", "run"]