# Gerando requirements.txt com pip

Hoje vou apresentar uma dica rápida da utilização do ```pip```, para gerar um arquivo com requirements (as dependências externas), que é extremamente útil ao realizar a distribuição de um software.

## Gerando requirements.txt

Um ponto comum quando estamos desenvolvendo um software para ser utilizado por terceiros está em garantir que o nosso código seja executado em outras plataformas além da máquina que esta sendo utilizada para o desenvolvimento.

Para que isso seja possível, um ponto essencial é garantir a exportação das soluções externas que estamos usando no nosso software.

Com o pip esse processo pode ser realizado através do comando ``pip freeze``, esse comando irá congelar as versões das dependências externas que estamos utilizando.

Em um terminal execute:

```
pip freeze
```

você ira obter uma saída como a apresentada a seguir:

```
nbformat==5.7.0
nest-asyncio==1.5.6
notebook==6.5.1
notebook_shim==0.2.0
numpy==1.23.4
packaging==21.3
pandas==1.5.1
pandocfilters==1.5.0
parso==0.8.3

```

Essa saída pode ser salva em um arquivo através do comando:

```
pip freeze >> requirements.txt
```


Links Interessantes:

- <https://pip.pypa.io/en/stable/>
