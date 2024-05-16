## SnakeUbuntu
This is a repository that contains a classic snake game version created using c and compiling the code in ubunto using the gcc compiler.
It utilizes the aid of the CLI-lib to recieve inputs from the user's keyboard and to have a timer. Since it doesn't compile in windows, we made a game that compiled in linux/Mac

--------------------------------------------------------------------------------------------
 ## Colaboradores 

Isabela Spinelli  (bela975 on github) <br/>
Maria Julia Pessoa (mariajuliapessoac on github) <br/>
Nicolas Sena (nicolasSenna on github) 

-------------------------------------------------------------------------------------------
## Bibliotecas utilizadas
### CLI-LIB
cli-lib : https://github.com/tgfb/cli-lib/blob/main/README.md

Cli-lib é uma biblioteca desenvolvida para a realização de aplicações e jogos em C, e com ela,
iremos gerenciar as telas do jogador e as entradas através do periférico do teclado.

Para utilizá-la, só precisamos pegar os arquivos de código-fonte (source) e cabeçalho
(header) deste repositório e adicioná-los ao nosso programa, substituindo o main 
neste repositório pelo nosso próprio.

------------------------------------------------------------------------------------------
## Requisitos
A biblioteca cli-lib funciona nos seguintes sistemas operacionais: <br/>
      Baseados em Linux (Ubuntu, etc)<br/>
      MacOS<br/>
Portanto, é necessário ter o GCC instalado para poder desenvolver o jogo.

-------------------------------------------------------------------------------------------
## Como executar e compilar nosso jogo? 
É preciso estar no sistema operacional Linux!
Nosso jogo foi feito no terminal do linux. Por isso, para compilá-lo é necessário instalar
o GCC.

bibliotecas do projeto:
Para construir a interface do nosso jogo e pegar os inputs dos periféricos dos usuários, 
contamos  com o auxílio das biblioteca cli-lib.

-------------------------------------------------------------------------------------------
## Como instalar a biblioteca cli-lib?
Para utilizá-la, é necessário somente pegar os source e o header file desse repositório 
e juntar ao nosso programa, trocando a main desse repositório pela nossa main.

--------------------------------------------------------------------------------------------

## Executando o jogo:

1.  para isso, é necessário abrir o terminal, e dar o comando
“ls” para visualizar todas as pastas do seu computador. 

2. em seguida é preciso dar cd e o nome da pasta do jogo em  seu computador. “cd Snakegame” por exemplo.

3. após entrar nela, com o gcc instalado claro, é só inserir o comando “gcc -o Snakegame main.c screen.c keyboard.c timer.c” e logo após essa execução inserir o comando  “./Snakegame” .
Pronto! O jogo já estará em execução.

Para que o código execute, preciso pegar a pasta do commit: https://github.com/bela975/SnakeGameC/commit/f73ae895dc821fa5855bc87a8428c8679c2375d8

OBS: Infelizmente o jogo está com problemas, então para acessar as diferentes partes do nosso menu, é preciso inserir o numero correspondente e além disso, dar enter.
