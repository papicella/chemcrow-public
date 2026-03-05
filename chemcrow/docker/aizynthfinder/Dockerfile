FROM python:latest
RUN pip install aizynthfinder[all] flask
COPY files/ .
COPY . .

EXPOSE 5000
ENTRYPOINT ["python"]

CMD ["app.py"]
