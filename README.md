# Laboratorio-de-Pesquisa-fundamentacao_5
T5- quinto ciclo iterativo

Neste presente documento será apresentado o relatório do quinto ciclo iterativo do desenvolvimento ágil de um software de jogo educacional.
onde nele terá:
# Planejamento.
A ideia inicial para esse ciclo era a implementação de:
1 - Confecção das letras e slots para orientação.
2 - Produção e implementação de sons.
3 - Criar protótipo para tutoriais.
Foi implementado o item 1 e 2, o protótipo para tutoriais não foi realizada. Para o próximo ciclo, planeja-se:

1 - Organizar o segundo painel
2 - Criar a opção de refazer o mesmo desafio
3 - Finalizar os tutorias escritos
4 - Implementar tutorias de áudio
5 - Fechar o game para teste beta

# Projeto ("Designing")
O design atual foi realizado na área do primeiro desafio de português, onde nele há 2 painéis,  1 definitivo e outro teste, para o definitivo 
Foi implementado os slots das letras juntamente com as letras.
foi adicionado as letras na frente do painel para ajudar o jogador na hora de selecionar a ordem das letras.
Foi adicionado mais um portal que inicialmente começa bloqueado, só é liberado quando o desafio do painel principal for concluído.
Toda a parte de cenário ainda é teste, melhorias serão feitas nos trabalhos posteriores.

## Modelo do lobby do game
![lobby](https://github.com/Laffaiety/Laboratorio-de-Pesquisa-fundamentacao_5/blob/main/LOBBY.png)

## Modelo do desafio 1
![lobby](https://github.com/Laffaiety/Laboratorio-de-Pesquisa-fundamentacao_5/blob/main/desafio%201.png)

## Codificação.

A codificação atual foi aplicada no painel 1, nele foi adicionado a lógica de esconder o painel assim que o desafio for concluído,
também foi adicionado a lógica de construir(chamar) as letras assim que uma determinada alavanca fosse acionada, assim como destruir(esconder) as letras se a alavanca for a opção incorreta.
Foi implementado a lógica de áudio para as interações com as alavancas, conclusão de desafio e erro caso a ordem seja incorreta, assim como o áudio principal do game.
Essas lógicas mesmo que estão funcionais no momento, ainda são testes então serão explicadas em trabalhos futuros.

## Event Graph Painel 1
![script](https://github.com/Laffaiety/Laboratorio-de-Pesquisa-fundamentacao_5/blob/main/painel%20log.png)

## Testes. 

### O vídeo a seguir mostra o teste do jogo no seu estado atual (Clique na imagem):
[![Vídeo de teste_0.4](https://github.com/Laffaiety/Laboratorio-de-Pesquisa-fundamentacao_5/blob/main/miniatura.png)](https://youtu.be/31WPOwCBi5w "Vídeo de Teste_0.5")
