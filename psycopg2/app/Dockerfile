FROM python:latest
WORKDIR /code
ADD requirements.txt requirements.txt
RUN pip install -r requirements.txt
COPY site_data.csv site_data.csv
COPY app.py app.py
CMD ["python3", "-u", "app.py"]