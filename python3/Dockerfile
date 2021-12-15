FROM python:3.10
#FROM python:latest
#FROM ubuntu:rolling

#RUN apt-get -y update && apt-get install -y \
# sudo \
# wget \
# vim

# update pip
RUN pip install --upgrade pip setuptools

# install JupyterLab
RUN pip install --no-cache-dir \
  jupyterlab \
  flake8 \
  jupyterlab_flake8 \
  black \
  isort \
  jupyterlab_code_formatter \
  lckr-jupyterlab-variableinspector
#  jupyterlab-git \
#  jupyterlab_widgets \
#  ipywidgets \
#  import-ipynb
 
# install ML packages 
RUN pip install --no-cache-dir \
  numpy \
  scipy \
  matplotlib
#  pandas \
#  scikit-learn \
#  pycaret \
#  japanize_matplotlib \
#  mlxtend \
#  seaborn \
#  plotly \
#  requests \
#  beautifulsoup4 \
#  Pillow \
#  opencv-python
 
# install extra packages
#RUN pip install --no-cache-dir \
#  pydeps \
#  graphviz \
#  pandas_profiling \
#  shap \
#  umap \
#  xgboost \
#  lightgbm
