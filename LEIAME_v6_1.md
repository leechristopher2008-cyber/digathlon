# Digathlon v6 — o que entrou (19/11/2026)

Feito por cima do `index.html` e do `dados.js` que você mandou às 21:34. É só trocar os dois arquivos.
As regras do Firebase não mudaram.

## Novidades
- **Régua de desempenho no fim:** mostra quanto você cavou, por quais camadas passou, seu recorde e sua média. O bicho anda em cima da régua.
- **Compartilhar virou imagem:** 1080×1350 com profundidade, patente, quadradinhos, as melhores respostas, a régua e o seu bicho vestido. Dá para compartilhar, salvar, copiar a imagem ou copiar o texto de antes.
- **Volta à superfície animada:** o bicho sobe o túnel de cabeça para cima, a cortina de terra fecha e o jogo recomeça.
- **Intro ao abrir:** as letras do logo caem uma a uma e a cortina abre. Um toque pula.
- **Tutorial opcional:** 4 quadros animados com uma pergunta de verdade. Abre na primeira visita e fica no menu.
- **Guarda-roupa:** 6 bichos (toupeira, tatu, coelho, raposa, texugo, pinguim), 9 chapéus, rosto, extras e roupas. A naja tem 6 cores e 3 chapéus.
- **Moedas e recompensas:** ganha por cavada, primeira cavada do dia, recorde, camada nova e baús enterrados. 13 conquistas.
- **Baús enterrados:** aparecem ao lado do túnel. Passou por um, ganhou moedas.
- **Cenário:** árvores, moitas, cerca, cogumelos, nuvens e vaga-lumes na superfície. Enfeites novos em cada camada e brilhos que piscam nas cavernas, no gelo, na rocha-mãe e no núcleo.
- **Animações:** botões, painéis entrando e saindo, menu, placar, anel de impacto ao pousar, riscos de velocidade, faíscas por camada.
- **Placar:** barra que mostra quanto falta para a próxima camada. Moedas ao lado do ☰.
- **12 perguntas difíceis demais** saíram do sorteio (as que não tinham nenhuma resposta comum ou rara).
- **`dados.js`:** voltei a lista `UNICAS` (perguntas de resposta única do modo Velocidade). Ela não estava no arquivo que você mandou; sem ela a Velocidade só fazia contas.

## O que NÃO entrou (fica para a próxima leva)
- Ranking, amizades e partida online pública. Precisam de regras novas no Firebase e de uma identidade que não mude a cada aba.
- Mais pixels no desenho base da toupeira e da naja (hoje a roupa é desenhada em cima do desenho do Christopher).

## Testado
- Teste novo (intro, tutorial, guarda-roupa, cavada do dia inteira, régua, imagem, volta): tudo passou, nenhum erro.
- Testes antigos do jogo sozinho e do online (naja, corrida, velocidade): passaram no arquivo novo.
- Só em navegador de teste (computador e iPhone simulado). Não testei em celular de verdade nem com o Firebase real.

## Detalhes
- Quem tem "reduzir movimento" ligado no aparelho, ou usa o modo acessível, não vê intro nem animações.
- O progresso novo (moedas, roupas, conquistas) fica salvo no aparelho, na chave `digV6`.
- A cavada de hoje pode mudar para quem ainda não começou, porque 12 perguntas saíram do sorteio.
