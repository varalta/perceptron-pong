# Aplicação de uma rede Perceptron no jogo Pong

## Introdução
Este projeto foi criado durante nossas aulas de "Computação Inspirada pela Natureza"[^1], ministradas pelo Prof. Dr. [@fbreve](https://github.com/fbreve).

No projeto, implementamos uma versão do jogo clássico Pong utilizando Python e a biblioteca Pygame, e incorporamos uma rede Perceptron para criar um adversário "inteligente". 

Nosso objetivo principal com o projeto foi explorar as capacidades de uma rede Perceptron para criar um adversário desafiador.

## Vídeo Demonstrativo

O vídeo do projeto[^2] pode ser assistido via YouTube: [https://www.youtube.com/watch?v=nGC0mN8vBis](https://www.youtube.com/watch?v=nGC0mN8vBis).

Neste vídeo, as quarto primeiras versões do projeto são apresentadas/demonstradas.

## Artigo Científico (preprint)
Nosso artigo, redigido após nossas implementações e testes, pode ser acessado aqui: [Aplicação de uma rede perceptron no jogo Pong](artigo.pdf).

## Como replicar

No ambiente Linux:

```console
git clone https://github.com/orlandosaraivajr/Pong.git
cd Pong/
virtualenv -p python3 venv
source venv/bin/activate
pip install -r requirements.txt
python pong_v5.py 2> /dev/null


```

No ambiente Windows:

```console
git clone https://github.com/orlandosaraivajr/Pong.git
cd Pong/
virtualenv venv
cd venv
cd scripts
activate.bat
cd ..
cd ..
pip install -r requirements.txt
python pong_v5.py

```

#### Notas de rodapé
[^1]: As aulas ocorreram no primeiro semestre de 2024, como parte do programa PPGCC-UNESP.
[^2]: O Orlando iniciou este projeto sozinho, mas após este vídeo apresentado em aula, entrei em contato com ele e seguimos o desenvolvimento do projeto em dupla. Em conjunto, fizemos a versão 5 - em que o bot Perceptron (player 2) joga contra o jogador humano (player 1) - e também escrevemos um artigo científico em que organizamos nossos experimentos e resultados.
