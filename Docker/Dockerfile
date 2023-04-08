FROM python:slim
RUN apt upgrade
WORKDIR ./app
COPY main.py ./app
COPY requirements.txt ./app
RUN pip install -r requirements.txt
CMD ["python","main.py"]
