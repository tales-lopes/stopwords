# Stopwords

Este é o trabalho final da ACIEPE: Programação paralela: das threads aos FPGAs - uma introdução ao tema. Realizado durante o semestre suplementar da Universidade Federal de São Carlos (UFSCar) em 2020.

# Utilização

Para utilizar o código proposto, existem duas opções.

Caso você não tenha um compilador de C++ ou não tenha instalado a biblioteca OpenMP, você pode utilizar um código feito no <a href = "https://coliru.stacked-crooked.com/a/eeb7769eeebb1b5d">Coliru</a>. Para utilizar o Coliru, basta clicar no botão `Edit` e depois em `Compile, like and run...`. Contudo, para utilizar essa opção, você precisa ter acesso à internet :(

A segunda opção só necessita de internet para baixar o arquivo `main.cpp` :) Mas, também é necessário ter o openmp instalado em sua máquina. Além disso, é aconselhável ter algum programa de <a href = "https://www.win-rar.com/start.html?&L=0">descompactação</a>.

Caso tenha GIT instalado na sua máquina, utilize o comando: `git clone https://github.com/tales-lopes/stopwords.git`. 
Ou vá à página inicial desse <a href = "https://github.com/tales-lopes/stopwords">repositório</a>, clique no botão `Code` e depois em `Download ZIP` e descompacte o arquivo e abra a pasta gerada no seu terminal. 

Ao abrir a pasta do projeto no terminal, primeiramente <b>compile</b> o código fonte `main.cpp` com o seguinte comando: `gcc main.cpp -o nome_programa -fopenmp`, sendo que `nome_programa` pode ser trocado por outro nome. Após isso, basta executar o programa com: `./nome_programa` e explore o programa à sua vontade.

<i>Allons-y,</i>
Tales Lopes.
