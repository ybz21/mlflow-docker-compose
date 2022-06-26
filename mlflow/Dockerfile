FROM python:3.9-slim-buster
# Install python packages
COPY requirements.txt /tmp
RUN pip install -r /tmp/requirements.txt -i https://pypi.tuna.tsinghua.edu.cn/simple
