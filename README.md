**Rafaela Tanaka Cardoso 24062611-2**

**Vitor Hugo da Costa 23234248-2**

# Jogo de Dominó - Casos de Teste

## Concepção do Desafio

O desafio consiste na criação de casos de teste para uma partida de Dominó entre 2 jogadores, utilizando JavaScript e o framework Jest.
A ideia é testar as principais regras do jogo, desde o início da partida e a distribuição das peças até as jogadas, compras de peças e identificação do vencedor.

Foram consideradas as regras do dominó tradicional, utilizando 28 peças, numeradas de 0 a 6, com 7 peças distribuídas para cada jogador no início da partida.

## Funcionamento dos Casos de Teste

Os casos de teste foram separados para verificar diferentes situações que podem acontecer durante uma partida.

Foram criados testes para verificar:

- Início de uma partida com 2 jogadores;
- Distribuição correta das peças;
- Quantidade de peças restantes no monte;
- Impedimento de partidas com quantidade incorreta de jogadores;
- Aceitação de jogadas válidas;
- Recusa de jogadas inválidas;
- Compra de peças quando não existe uma jogada possível;
- Passagem de vez quando não existem mais peças para comprar;
- Impedimento de jogadas fora da vez;
- Identificação do vencedor quando um jogador fica sem peças;
- Encerramento da partida quando o jogo fica bloqueado;
- Comparação da pontuação dos jogadores e identificação de empate;
- Impedimento de novas jogadas após o encerramento da partida.

Os testes foram organizados utilizando o `describe()` para agrupar os cenários e o `test()` para identificar cada situação que deve ser verificada.

## Tecnologias Utilizadas

- JavaScript
- Jest

## Quantidade de Testes

Foram elaborados 20 casos de teste, considerando situações válidas e inválidas que podem acontecer durante uma partida de Dominó.

O objetivo é verificar se as regras estão sendo respeitadas e se o jogo apresenta o comportamento esperado em cada situação.
