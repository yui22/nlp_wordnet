 FROM python:3.8

 RUN apt-get update && apt-get -y upgrade
 RUN pip install numpy==1.20.0 \
     pip install pandas==1.2.1 \
     pip install spacy==3.0.1 \
     pip install nltk==3.5 \
     pip install matplotlib scikit-learn

RUN python -m spacy download en_core_web_sm

RUN pip install jupyter jupyterlab

CMD [ "/bin/bash" ]