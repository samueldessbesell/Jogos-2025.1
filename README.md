# README - Sistema de Minijogos em C

## 1. INTRODUÇÃO
No universo da programação, o desenvolvimento de jogos é amplamente considerado um dos desafios mais complexos, devido à quantidade de detalhes e regras que precisam ser seguidos. No entanto, quando finalizados, proporcionam grande satisfação e aprendizado aos desenvolvedores.
Este projeto tem como objetivo permitir que os alunos apliquem os conhecimentos adquiridos em programação estruturada na linguagem C, desenvolvendo um sistema que contém minijogos interativos.

## 2. OBJETIVOS
O projeto busca desenvolver as seguintes competências nos alunos:
- Resolução de problemas;
- Raciocínio lógico e algorítmico;
- Trabalho em equipe e desenvolvimento de competências interpessoais;
- Aplicação prática dos conceitos fundamentais da linguagem C.

## 3. DESENVOLVIMENTO DA ATIVIDADE
O projeto poderá ser desenvolvido em equipe de até DOIS estudantes e resultará na entrega dos seguintes artefatos:
1. O código-fonte principal do jogo desenvolvido em C;
2. Um repositório no GitHub contendo o código e um arquivo README explicativo sobre o projeto e os integrantes da equipe;
3. Um seminário de apresentação e defesa do código desenvolvido.

O jogo deverá utilizar o console para a interface gráfica e a interação com o usuário. O objetivo do projeto é a criação de um arcade contendo três minijogos.

## 4. DESCRIÇÃO DO JOGO
O sistema será composto por três minijogos, acessíveis a partir de um menu principal. Ao iniciar o programa, o usuário visualizará a seguinte interface:

O programa permanecerá em execução até que o usuário escolha a opção de sair. Ao selecionar um minijogo, será exibida uma breve descrição antes do início da partida.

### 4.1 Pergunta e Resposta
Neste jogo, o computador apresenta uma pergunta com quatro alternativas e solicita que o usuário escolha a resposta correta. Após a seleção, o sistema indicará se a resposta está correta ou incorreta. Caso seja incorreta, será exibida a resposta correta.
- O jogo conterá um total de cinco perguntas fixas;
- A ordem das perguntas e suas respostas não precisa ser alterada entre as rodadas;
- Ao finalizar, o jogador poderá optar por jogar novamente ou voltar ao menu principal.

### 4.2 Cobra na Caixa!
A história do jogo se passa dentro de uma tumba egípcia onde dois exploradores ficaram presos. No centro da sala, há cinco caixas: uma delas contém o botão para abrir a porta, enquanto uma outra esconde uma cobra mortal. A cada rodada, o local do botão e da cobra muda de caixa de forma aleatória, aumentando o desafio e a imprevisibilidade do jogo.
- Cada jogador deve escolher um nome a partir de uma lista de sete opções predefinidas, e o computador sorteará quem começará;
- O jogador escolhido seleciona uma caixa, e o sistema informará se há uma cobra, o botão ou se está vazia;
- O jogo prosseguirá até que alguém encontre a cobra (perde) ou o botão (vence);
- Ao término, o jogador poderá optar por jogar novamente ou retornar ao menu principal.

### 4.3 Gousmas War
Neste jogo de estratégia, os jogadores controlam criaturas chamadas Gousmas, que podem se dividir e acumular fúria ao serem atacadas.
- Cada jogador inicia com duas Gousmas, cada uma com nível de fúria 1;
- Quando uma Gousma ataca outra, transfere todo o seu nível de fúria para a Gousma atacada;
- Se uma Gousma atingir um nível de fúria maior que 5, ela se desintegra;
- O jogador pode optar por dividir uma Gousma, transferindo uma parte da fúria para uma nova Gousma (respeitando o limite de duas Gousmas por jogador);
- O jogador que perder todas as suas Gousmas será derrotado;
- Ao final do jogo, o jogador pode optar por reiniciar ou retornar ao menu principal.

## 5. AVALIAÇÃO
A avaliação do projeto será realizada conforme os seguintes critérios:

| Critério | Pontuação |
|-----------|------------|
| Entrega do código conforme os requisitos | 1,8 pontos |
| Apresentação e defesa do código | 1,0 ponto |
| Repositório no GitHub (código e README) | 0,5 pontos |
| Acompanhamento do desenvolvimento | 0,7 pontos |

**Observação:** Caso tenham sido utilizados trechos de código de outras fontes (por exemplo, Stack Overflow, ChatGPT, etc.), os alunos deverão referenciá-los no arquivo README do GitHub. Além disso, deverão apresentar a conversa com a IA durante a defesa do projeto para demonstrar como a ferramenta foi utilizada no desenvolvimento.

