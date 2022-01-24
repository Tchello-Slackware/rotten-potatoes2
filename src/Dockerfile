FROM python:3.8-slim-buster
WORKDIR /app
COPY requirements.txt .
RUN python -m pip install -r requirements.txt
COPY . /app/
EXPOSE 5000
<<<<<<< HEAD
#CMD ["gunicorn", "--workers=2", "--bind", "0.0.0.0:5000", "-c", "config.py","app:app"]
#CMD ["gunicorn", "--workers=2",  "-c", "config.py","app:app"]
=======
CMD ["gunicorn", "--workers=3", "--bind", "0.0.0.0:5000", "-c", "config.py","app:app"]
>>>>>>> 4b930d644e6753d78d6d2d95b0c6e2d01c2784b9

