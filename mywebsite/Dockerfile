FROM python:3
COPY . /app
WORKDIR /app
RUN pip install django
EXPOSE 8000
CMD ["python3", "manage.py" "runserver" "0.0.0.0:8000"]