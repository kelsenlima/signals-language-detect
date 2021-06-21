# Signal Language
<h1 align="center">
  <br>
  <img src="https://github.com/kelsenlima/signals-language-detect/blob/main/Tensorflow/Signal%20Languade%20Detect%20-%20Deep%20Learning.gif" alt="Kelsen Lima" height="320" width="320">
</h1>

## :blush: **Descrição**

Signal Language é um estudo técnico para aprendizado de Deep Learning, realizando coleta de imagens para estudo de máquina, podendo ser imagens de expressões faciais, objetos e dentre outros itens, tendo apenas que adaptar o modelo.

Signal Language executa a interpretação da linguagem Libras – Linguagem Brasileiro de Sinais, o modelo apresentado possui o aprendizado das expressões: ‘Olá, Sim, Não, Obrigado e Te amo’.

## :dizzy: **Roteiro**

** Checklist **
Certifique-se de possuir as bibliotecas abaixo, caso contrário execute a instalação com comando abaixo:

1.	pip install virtualenv
2.	pip install --upgrade tensorflow
3.	pip install PyQt5 (para o funcionamento LabelImg)
4.	Configurar o Protoc
5.	Clone o repo git clone https://github.com.br/tensorflow/model (salve em uma pasra fixa, tipo C:\Package)
6.	Execute os comandos abaixo para configuração

C:\Packages\models\research>protoc object_detection/protos/*.proto --python_out=.
C:\Packages\models\research>cp object_detection/packages/tf2/setup.py .
C:\Packages\models\research>python -m pip install .

Observação: Deverá ser configurado a path de variavel de sistema do Protoc.

Caso queira instalar o Junyper Notebook- execute pip install notebook
Neste caso não teremos a instalação do pacote Anaconda.

## :zap: **Tecnologia**

<img align="left" alt="Python" width="42px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/python/python.png" />
<img align="left" alt="Jupyter Notebook" width="42px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/jupyter-notebook/jupyter-notebook.png" />

<br>
<br>

## :handshake: **Referências**

-   ⭐️ TensorFlow - https://github.com/tensorflow/tensorflow
-   ⭐️ LabelImg - https://github.com/tzutalin/labelImg
