FROM python:3.14.5
RUN pip install aizynthfinder[all] flask
COPY files/ .
COPY . .

EXPOSE 5000
ENTRYPOINT ["python"]

CMD ["app.py"]
