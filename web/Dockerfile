FROM python:3.13.0rc3-slim-bullseye
WORKDIR /app
COPY . .
ENV FLASK_APP=app.py
ENV FLASK_RUN_HOST=0.0.0.0
ENV FLASK_ENV=development
RUN pip install -r requirements.txt
EXPOSE 5000
CMD ["flask", "run"]
