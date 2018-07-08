FROM nvcr.io/nvidia/tensorflow:18.06-py3

RUN pip install numpy matplotlib
RUN pip install jupyter==1.0.0
RUN pip install keras==2.2.0

CMD jupyter notebook --allow-root --ip="0.0.0.0"

EXPOSE 8888
