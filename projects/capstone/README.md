# Nanodegree Engenheiro de Machine Learning
## Projeto final

### Instalação
Este projeto requer **Python 3.\*** e as seguintes bibliotecas do Python instaladas:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [IPython](https://ipython.org/)
- [keras](https://keras.io/)
- [librosa](http://github.com/librosa/librosa)

Você também precisará ter o software instalado para executar e executar o [Jupyter Notebook](http://ipython.org/notebook.html)

Se você ainda não tem o Python instalado, é altamente recomendado que você instale a distribuição [Anaconda] (http://continuum.io/downloads) do Python, que já tem os pacotes acima e mais incluídos.

Para ajudar na criação do ambiente pode-se utilizar os seguintes comandos da **Anaconda**:
- Para Windows:

  `conda create --name capstone --file requirements/spec-file-windows.txt` ou

  `conda env create -f requirements/environment-windows.yml`

- Para Linux:
 
  `conda create --name capstone --file requirements/spec-file-linux.txt` ou
 
  `conda env create -f requirements/environment-linux.yml`

### Código
Os códigos são fornecidos nos arquivos `Capstone-deepLearning.ipynb`e `Capstone-CNN.ipynb`.

### Execução
Em um terminal ou janela de comando, navegue até o diretório de projeto de nível superior `report-capstone/` (que contém este README) e execute um dos seguintes comandos:

```bash
ipython notebook Capstone-deepLearning.ipynb
ipython notebook Capstone-CNN.ipynb
```  
ou
```bash
jupyter notebook Capstone-deepLearning.ipynb
jupyter notebook Capstone-CNN.ipynb
```

Isso abrirá o software do Notebook Jupyter e o arquivo de projeto no seu navegador.

### Dados
Os dados utilizados no projeto foram retirados da competição [TensorFlow Speech Recognition Challenge](https://www.kaggle.com/c/tensorflow-speech-recognition-challenge/data) do kaggle.

A base de dados contém subpastas com comandos de voz de um segundo, com o nome da pasta sendo a palavra dita no clipe de áudio.

As palavras no conjunto de áudio são: bed, bird, cat, dog, down, eight, five, four, go, happy, house, left, marvin,
nine, no, one, on, one, right, seven, sheila, six, stop, three, two, up, wow, yes e zero.