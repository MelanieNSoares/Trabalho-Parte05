# Projeto Trabalho

# Equipe
* Melanie Nellen Soares RA: 241997

# Descrição Resumido do Projeto
* Criação de um jogo de niveis utilizando conceitos de programação orientado a objetos e 'cellular automata' para um trabalho de Unicamp

# Vídeo do Projeto

# Diagrama Geral de Componentes




# Componente Table
## Interfaces
  * Interfaces associados a esse componente:
  
Campo | Valor
----- | -----
Classe | `<caminho completo da classe com pacotes>` <br> Exemplo: `pt.c08componentes.s20catalog.s10ds.DataSetComponent`
Autores | Melanie N Soares
Objetivo | Tratar os dados do tabuleiro
Interface | ITable

## Detalhamento das Interfaces

### Interface ITable

Método | Objetivo
-------| --------
setTable | 
updateTable |
checkNeighbors|
deletePieces|
showTable|

~~~
public interface ITable {

 public void setTable(int level);
 public void updateTable();
 public void checkNeighbors();
 public void deletePieces();
 public void showTable();
 
}
~~~








# Componente Scoreboard

## Interfaces
  * Interfaces associados a esse componente:
  
Campo | Valor
----- | -----
Classe | `<caminho completo da classe com pacotes>` <br> Exemplo: `pt.c08componentes.s20catalog.s10ds.DataSetComponent`
Autores | Melanie N Soares
Objetivo | Armazena e trata dados do jogo e jogador 
Interface | IScoreboard

## Detalhamento das Interfaces
### Interface IScoreBoard

Método | Objetivo
-------| --------
updatePoints | 
updateLevel |
amountOfPieces|

~~~
public interface IScoreboard {
 
 public void updatePoints(int points);
 public void updateLevel(int level);
 public void updateCount(int count);
 public int getPoints();
 public int getLevel();
 public int getCount();
 
}
~~~











# Componente Piece
## Interfaces
  * Interfaces associados a esse componente:
  
Campo | Valor
----- | -----
Classe | `<caminho completo da classe com pacotes>` <br> Exemplo: `pt.c08componentes.s20catalog.s10ds.DataSetComponent`
Autores | Melanie N Soares
Objetivo | Tratar as peças presentes no jogo
Interface | IPiece

## Detalhamento das Interfaces

### Interface IPiece

Método | Objetivo
-------| --------
calculateMovement|

~~~
public interface IPiece {
 public int[] calculateMovement(Table table);
 }
~~~




# Componente CanonLauncher
## Interfaces
  * Interfaces associados a esse componente:
  
Campo | Valor
----- | -----
Classe | `<caminho completo da classe com pacotes>` <br> Exemplo: `pt.c08componentes.s20catalog.s10ds.DataSetComponent`
Autores | Melanie N Soares
Objetivo | Simular e armazenar peças de um canhão
Interface | ICanonLauncher

## Detalhamento das Interfaces

### Interface ICanonLauncher

Método | Objetivo
-------| --------
setCanon | 
getPiece |
updateLauncher|

~~~
public interface ICanonLauncher {

 public void setCanon();
 public Piece getPiece();
 public void updateLauncher();

~~~





