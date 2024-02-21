FROM python:3.10
USER root

RUN apt-get update && \
    apt-get -y install --reinstall ca-certificates && \
    apt-get -y install software-properties-common && \
    pip install --upgrade pip && \
    apt-get install -y sudo wget vim curl gawk make gcc

# Install Basic Packages
RUN pip install ipykernel jupyter && \
    pip install scikit-learn && \
    pip install matplotlib && \
    pip install feature-engine && \
    pip install pandas