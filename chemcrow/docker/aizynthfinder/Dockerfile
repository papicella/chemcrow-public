FROM python:3.15.2
RUN pip install aizynthfinder[all] flask
COPY files/ .
COPY . .

EXPOSE 5000
ENTRYPOINT ["python"]

CMD ["app.py"]
