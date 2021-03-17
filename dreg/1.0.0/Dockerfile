FROM ubuntu:18.04
LABEL author="Sruthi Suresh"
LABEL author="Edmund Miller"

RUN apt-get install r-base-core libssl1.0.0 libssl-dev
RUN wget https://github.com/Danko-Lab/dREG/archive/master.zip && unzip master.zip && master.zip \
&& cd dREG-master && make R_dependencies && make dreg
