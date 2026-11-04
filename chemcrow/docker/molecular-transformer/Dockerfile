FROM python:3.15.2
WORKDIR /app

RUN pip install rdkit-pypi==2022.3.1
RUN pip install OpenNMT-py==2.2.0 "numpy<2.0.0"

COPY . .
COPY input.txt .
COPY models/ .
CMD ["python", "app.py"]

