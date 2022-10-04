FROM python:3.10-slim

RUN apt-get update && apt-get install -y git

RUN pip install --upgrade pip
RUN pip install jupyterlab ipywidgets matplotlib
RUN pip install pytest

RUN pip install qiskit
RUN pip install qiskit[visualization]
RUN pip install git+https://github.com/qiskit-community/qiskit-textbook.git#subdirectory=qiskit-textbook-src



#RUN apt-get install gcc g++ python3-dev
RUN apt-get install build-essential
RUN pip install python-sat[pblib,aiger]