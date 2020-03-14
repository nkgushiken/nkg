FROM python:3.6-slim 
#FROM imagem

WORKDIR /app
#WORKDIR cria diretório de trabalho

RUN pip install Flask
#RUN instala o software dentro do container

# COPY . /app
# COPY copia arquivos locais para dentro do container 

ADD . /app
# ADD copia arquivos remotos ou locais para dentro de imagens 
#https://stackoverflow.com/questions/24958140/what-is-the-difference-between-the-copy-and-add-commands-in-a-dockerfile

ENTRYPOINT [ "python" ]


CMD [ "app.py" ]