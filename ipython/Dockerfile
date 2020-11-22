FROM continuumio/miniconda3
LABEL maintainer=@jimmyTGB
RUN conda update conda && \
    conda install --quiet --yes ipython && \
    conda clean -tipsy
CMD ["ipython"] 
