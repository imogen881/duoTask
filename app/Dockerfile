FROM python:3.6
COPY . .
RUN pip install -r requirements.txt
ARG NAME="Imogen"
ENV YOUR_NAME=$NAME
EXPOSE 5500
ENTRYPOINT ["python", "app.py"]