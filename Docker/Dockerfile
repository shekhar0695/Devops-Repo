FROM python:slim
RUN apt update
WORKDIR /app
COPY main.py ./app
COPY requirements.txt ./app
RUN pip -r requirements.txt
CMD ["python","main.py"]
ENTRYPOINT ["/bin/bash"]
