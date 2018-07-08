FROM python:3.6.4

RUN pip install numpy matplotlib tensorflow keras jupyter

WORKDIR /playbooks

EXPOSE 8888

CMD jupyter notebook --allow-root --ip=0.0.0.0
