# hello-world
JAR = just another repository (short description following "Read the Guide"). 

# Aplicativo de identificao de digitos escritos manualmente.

## [Demo Online](https://flask-mnist.herokuapp.com/)

## Instalacao

Clone o repositÃƒÂ³rio ou baixe o pacote zip.

Instale os pacotes necessÃƒÂ¡rios:

```bash
$ pip install -r requirements.txt
```

## Treinar o modelo

O aplicativo web depende do modelo treinado. Este processo acontece no arquivo TFLearn_Digit_Recognition.ipynb. Basta executar todo o notebook para iniciar, treinar e salvar o modelo treinado como MNIST.tfl

## Executar o aplicativo web

Com as dependencias instaladas, execute os seguintes passos para rodar o web app:

```bash
$ export FLASK_APP=app.py
$ flask run
```
