FROM python:3.8

WORKDIR /app

COPY requirements.txt /app/

COPY . /app/

EXPOSE 5000

# Install dependencies with pip
RUN pip install -r requirements.txt

# Run Flash serv
CMD ["flask", "run", "--host=0.0.0.0"]