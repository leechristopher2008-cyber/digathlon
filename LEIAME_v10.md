# TOUPIX v10 (22/11/2026) — parte 1 + animações (v10b) + abertura e relíquias (v10c)

Arquivos do jogo: `index.html` e `dados.js` (os dois, juntos, na mesma pasta). `dados.js` é o mesmo da v9.

## O que mudou
1. **Nome novo: TOUPIX.** Título da aba, logo da tela inicial, abertura, cartão e texto de compartilhar.
   (Por dentro, o endereço do banco e os dados salvos no aparelho continuam com o nome antigo de propósito: assim ninguém perde moedas, bichos nem sequência.)
2. **Competitivo, tempo esgotado:** agora tira **1 coração** e vai para a próxima pergunta. Só acaba quando os 3 corações zeram.
3. **Competitivo, pular:** custa **1 coração** (o botão mostra "−1❤"). No último coração o pulo é barrado e aparece um aviso.
4. **Botão ✕ CANCELAR CAVADA** durante a Cavada do Dia, a Livre e o Competitivo. Dois toques (o segundo confirma). O bicho sobe e o jogo volta para a tela inicial.
   - No PC fica no canto de cima, à esquerda. No celular fica logo abaixo da pergunta, só com o ✕.
   - Cancelar a Cavada do Dia funciona igual ao F5 de antes: a cavada não conta e pode ser refeita.
5. **Guarda-roupa:** o título fica no centro exato da janela (no celular o título continua escondido, como já era, para caber o botão de voltar).

## O que foi testado (em navegador de teste, PC e celular)
- 26 checagens novas da v10 + 14 do botão de cancelar nos outros modos (não aparece em Naja Party, Roda da Toca, Ver as Camadas, menu, loja).
- Os testes antigos (v6 a v9, solo, online) rodaram de novo nesta versão.
- **Não testado:** celular de verdade e partida online com o Firebase real (só com banco simulado).

## Atenção antes de publicar
- Esta versão **não inclui o último envio do seu amigo no repositório**. Publicar por cima do site troca o que ele subiu por esta versão. Combine com ele antes.
- As regras do banco não mudaram.

## v10b (22/11, madrugada): animações
6. **Cavada de verdade, por bicho.** Cada um dos 14 bichos ganhou um desenho novo de mergulho (visto de costas, patas da frente esticadas, 4 quadros). Não é mais o desenho em pé girado de lado. O chapéu/capacete, a roupa, a mochila, a capa, as asas e o jato aparecem nessa pose.
   - Toupeira, tatu, texugo, coelho, raposa, gato, caramelo: patas alternando (nado crawl).
   - Sapo: impulsos de rã com as pernas de trás. Coruja e pinguim: asas/nadadeiras batendo.
   - Jabuti: casco girando como broca, com faíscas. Capivara e panda: patada pesada com onda de terra. Dinossauro: rabo balançando e terra arrancada.
   - Terra voando dos lados, faíscas na rocha, facho da lanterna para baixo e tremor leve conforme a velocidade.
7. **Túnel irregular:** paredes onduladas, sombra, pedrinhas, marcas de garra, boca mais larga e fundo arredondado. O túnel continua lá quando o bicho sobe.
8. **Subida:** o bicho escala o túnel de cabeça para cima e dá um salto mortal ao sair.
9. **Tela inicial viva:** o bicho anda de um lado para o outro (com poeirinha), pula, olha para o céu e fareja a toca.
10. **Ver as camadas:** 1/3 da velocidade, e ainda mais devagar ao entrar em cada camada.
11. **Guarda-roupa:** trocar de aba desliza os itens sem fechar a sala. Equipar chapéu: ele cai e quica. Roupa/extra: giro com estrelinhas. Naja: bote.

Testado (PC e celular, navegador de teste): 18 checagens novas (14 bichos com pose, bicho andando, mergulho, passeio, guarda-roupa) + todos os testes antigos. **Não testado em celular de verdade.**

O que eu NÃO fiz desta lista: o desenho de mergulho não mostra óculos/bigode/gravata (ficam na frente do bicho, que está de costas).

## v10c (22/11): abertura animada e subsolo com relíquias
12. **Abertura animada (2 segundos):** no escuro da terra a luz da lanterna sobe, o bicho que você está usando cava para cima, fura a grama, salta girando e as letras TOUPIX estouram; ele pousa embaixo do nome e a tela abre. Toque ou tecla pula na hora.
13. **Relíquias ao lado do túnel** (lado esquerdo), uma a cada ~230 m, diferentes em cada camada:
    - Terra: baú de madeira. Pedra: amonite, crânio antigo, costelas, pegada petrificada.
    - Cavernas: ametista e esmeralda. Gelo: quartzo de gelo. Magma: rubi.
    - Rocha-mãe: totem, pilar antigo, baú rúnico. Núcleo: cristal do núcleo.
    - Brilham mais quando o bicho chega perto. Ao passar, sobe o nome e as moedas ("+5 🪙 Crânio antigo").
14. **Regras das moedas de relíquia** (para ninguém ficar rico só cavando):
    - Cada relíquia paga **uma vez por dia** (2 a 10 moedas, mais fundo paga mais). No mesmo dia, de novo, só mostra o nome.
    - **Teto de 60 moedas de relíquia por dia.**
    - Só na **Cavada do Dia** e na **Livre**. Não paga no Competitivo, na corrida, na Naja Party, na Roda da Toca nem em "Ver as camadas".
    - Os baús antigos (lado direito) continuam como eram.
15. **Desenhos refeitos com o dobro de detalhe** (contorno, 3 tons e brilho): fósseis, cristais, baús, ruínas. Também aparecem espalhados pela terra como enfeite.
16. **Subsolo mais vivo:** minhocas se mexendo na terra de cima e lava ondulando nas bordas da camada de magma.
    Com "menos movimento" ligado, as relíquias aparecem paradas e a lava e as minhocas somem.

Testado (PC e celular, navegador de teste): 25 checagens novas das relíquias (paga uma vez, não paga de novo no mesmo dia, volta a pagar no dia seguinte, teto, modos que não pagam, dado salvo estragado) + todos os testes antigos (v6 a v10b, solo, online). **Não testado em celular de verdade.**

## Ainda não entrou
Perfil e sequência salvos na nuvem (precisa de uma regra nova no banco, publicada por você ou pelo seu amigo). Ícones do menu e da loja redesenhados.
