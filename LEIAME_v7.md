# Digathlon v7 — o que entrou (20/11/2026)

Feito por cima do v6. É só trocar o `index.html` (o `dados.js` é o mesmo do v6, sem nenhuma mudança).
As regras do Firebase não mudaram.

## Naja Party (arena)
- **A naja fica ao lado de quem está com a vez**, com o pé alinhado ao montinho e olhando para o jogador. Sem espaço à direita, ela vai para a esquerda.
- **Passou a vez:** ela vai em arco até o próximo, soltando fagulhas douradas e com chocalho. O aviso "A naja está com..." só troca quando ela chega.
- **Olhos acendem** conforme o tempo do turno acaba. Ela é 25% maior e balança mais rápido perto do bote.
- **VOCÊ** fica embaixo, maior (1,35x) e com brilho dourado. Quem está com a vez nunca fica atrás do vizinho.
- **Balões** em cima da cabeça, escuros com borda âmbar.
- **Roda mais larga** no computador (até 35%), sem ninguém sair da tela.
- **Caverna nova:** arcos de rocha, estalactites com gota caindo, cristais azuis com brilho frio, tochas com fagulhas, pedras rúnicas em volta do poço, ossos, moedas, rachaduras que pulsam e vinheta mais forte.

## Cavada
- **Câmera presa no bicho:** na subida ("voltar pra superfície") e nas descidas ele não sai mais da tela.
- **Descida 45% mais lenta**, com teto de 5,5 s por queda (as quedas muito fundas não chegam aos 45%). A corrida online ficou como estava, porque é contra o relógio.
- **Subida mais calma** (até 1 s a mais).
- **Régua lateral nova:** termômetro com as cores das camadas e o SEU bicho (com a roupa) deslizando, com os metros ao lado (no celular, sem os metros).

## Menu e telas
- **Botão "← MENU"** dentro de Configurações, Estatísticas, Coleção, Como jogar, Guarda-roupa e Recompensas.
- **Painéis** entram com fade + subida curta e o fundo escurece de leve.
- **Guarda-roupa e Recompensas abrem no começo da lista** (antes abriam rolados até o fim).
- **Botão principal de cavar** em estilo arcade: dourado, em relevo, com picareta balançando e afundando ao clicar.
- **Sons:** clique nos botões e um som ao abrir painel (comprar e vestir já tinham som).

## O que NÃO entrou (fica para a próxima leva)
- Bichos novos com corpo próprio (tatu-canastra, texugo, suricato, lebre, axolote, tamanduá) e mais pixels por desenho.
- +8 roupas e +8 acessórios.
- 4 cenários de superfície (amanhecer, deserto, floresta, tundra).
- Colecionáveis nos marcos de 1.000 / 2.500 / 5.000 / 8.500 m e fósseis novos.
- Extras dos modos (combo e blocos especiais na Cavada Livre, fantasmas dos rivais no Competitivo, suspense na roleta).
- Título caindo com poeira na abertura.
- Sons diferentes por dureza da camada e fanfarra de achado.

## Testado
- 6 roteiros automáticos no arquivo final (`index.html` 03dac156): arena com 4 jogadores (computador, tela média e iPhone simulado), 8 jogadores no celular, duas partidas seguidas, sair da sala e abrir a Roda da Toca na mesma página, cavada do dia inteira, subida, menu, e os testes antigos do jogo sozinho e do online. Tudo passou, nenhum erro.
- Só em navegador de teste, com um Firebase de mentira. Não testei em celular de verdade nem com o Firebase real.
- Som: confirmei que as chamadas acontecem, mas não ouvi (navegador de teste não tem áudio).

## Detalhes
- Com 7 ou 8 jogadores num celular a roda fica apertada (os nomes dos vizinhos se encostam). A naja fica menor nesse caso.
- Quem tem "reduzir movimento" ligado não vê as animações novas.
