FROM ubuntu:latest

LABEL version="1.0.0" description="Minha imagem" maintainer="Lucas Nobre<lnobreteixeira@yahoo.com.br>"

RUN apt-get update && apt-get -y --no-install-recommends install htop &&rm -rf /var/lib/apt/lists/lists/*

RUN cd / && mkdir docs

CMD /bin/bash
