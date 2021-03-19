FROM cyversevice/jupyterlab-scipy:latest

USER root

#install some linux packages
RUN apt-get update \
	&& apt-get install -y python3-pip

RUN pip3 install strym
RUN pip3 install gensim

# install some R packages

USER jovyan
