FROM ubuntu:20.04

# COPY asciidoctor-vscode-3.0.0.vsix /tmp/


RUN ln -fs /usr/share/zoneinfo/Asia/Tokyo /etc/localtime && \
    apt-get update && apt-get install -y \
    nodejs \
    npm 

RUN apt-get update && apt-get install -y \
    build-essential \
    cmake \
    default-jdk \
    fonts-lyx \
    fonts-noto-cjk \
    gcc \
    graphviz \
    graphviz-dev \
    libssl-dev \
    libxml2-dev \
    libpangocairo-1.0-0 \
    make \
    ruby-dev \
    ruby-full \
    rubygems \
    vim \
    zlib1g-dev 

RUN gem install asciidoctor 
RUN gem install asciidoctor-latex --pre
RUN gem install asciidoctor-pdf
RUN gem install coderay
RUN gem install asciidoctor-diagram
