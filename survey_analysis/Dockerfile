FROM jupyter/datascience-notebook:latest
RUN pip3 install -U pip google-api-python-client
RUN conda install -y matplotlib-venn altair --channel conda-forge
RUN conda install -y nltk
RUN conda update -y bokeh
RUN conda install -y rise --channel damianavila82
RUN conda install -y wordcloud --channel amueller
