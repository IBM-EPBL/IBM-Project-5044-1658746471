FROM python:3
WORKDIR /app
COPY ./requirements.txt .
RUN pip install -r requirements.txt
COPY . .
EXPOSE 9090
CMD [ "python", "app.py" ]