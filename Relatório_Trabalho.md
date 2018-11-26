O seguinte relatório refere-se ao trabalho de Algoritimos e programação II no qual nosso grupo deveria desenvolver um jogo de batalha naval em C++.

O desenvolvimento do jogo se deu através de encontros na casa de um dos participantes do grupo, onde foi-se discutido e desenvolvido quase toda a metodologia.

A maior parte do desenvolvimento se deu através do Microsoft Visual Studio 2017, mas também foi utilizado o mesmo compilador utilizado em sala de aula (Dev C++) os quais apresentaram algumas diferenças de compilação, como por exemplo, no Visual Studio 2017 o compilador pulava a tela a qual o usuário informava seu "nome de jogador", algo que não ocorreu através do Dev C++.

Para a armazenar a quantidade de embarcações foi utilizado a estrutura de dados "Struct" nomeada Barco contendo todas as 6 embarcações utilizadas no jogo.

Para a criação do tabuleiro foi utilizado uma matriz tamanho 14x14, para representar a água foi utilizado o carácter: "~", para representar o barco foi utilizado: "#", para disparo: "x" e para quando o barco for atingido: "$".

Para o restante das funcionalidades e ações do jogo foi utilizado a estrutura de dados "Function" como por exemplo a função GerarMenuPrincipal a qual imprime para o usuário as opções disponiveis do menu principal e recebe a decisão do mesmo.

O jogo ocorre da seguinte maneira: o usuário começara em um menu principal no qual ele devera escolher uma das seguintes opções: Iniciar jogo, Instruções do Jogo ou Finalizar jogo, caso o usuário escolha "Iniciar jogo" uma nova tela surgira solicitando que o mesmo informe um nome no qual sera indicado no topo de seu tabuleiro, o qual seria seu "nome de jogador", caso a escolha seja "Intruções do Jogo", o mesmo recebera uma tela informando como o jogo se desenvolvera, caso o usuário escolha "Habilidades Para Barcos" mostrara habilidades especiais das embarcações, e a ultima opção "finalizar jogo" fará com que uma segunda tela pedindo para o usuário confirmar ou não a saida do jogo seja imprimida, caso a resposta seja "S" o jogo se encerrara, caso a resposta seja "N" ele voltara a tela do menu principal.

Após a escolha de seu "nome de jogador" o usuário tera que escolher as posições de suas 6 embarcações indicadas em um mini menu com a numeração e o tamanho de cada embarcação para que o usuário escolha qual ele ira posicionar em seu tabuleiro e se o mesmo sera posicionado na horizontal ou vertical.

Terminado todos os passos relatados acima a partida começara e as primeiras coordenadas a serem atacadas serão informadas pelo usuário e o resultado da rodada de ataques do usuário e do computador serão imprimidas, o resultado da ação podendo ser "Água" ou "Barco atingido", a tela de jogo também conta com um placar indicando o quanto de vida o jogador e o computador possui (vida diminui ao acertar a embarcação).

O jogo terminara quando todas as embarcações do usuário ou do computador forem destruidos, caso o jogador ganhe, uma mensagem dizendo: "PARABÉNS JOGADOR "Nome do Jogador! Voce Venceu!!" sera imprimida, caso o computador ganhe, a seguinte mensagem sera imprimida: "JOGADOR "Nome do jogador". QUE PENA, VOCÊ PERDEU!"

