FROM airflow-base

COPY requirements.txt .
RUN pip install -r requirements.txt

COPY validate.py /validate.py

ENTRYPOINT ["python", "validate.py"]