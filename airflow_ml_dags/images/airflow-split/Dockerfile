FROM airflow-base

COPY requirements.txt .
RUN pip install -r requirements.txt

COPY split.py /split.py

ENTRYPOINT ["python", "split.py"]