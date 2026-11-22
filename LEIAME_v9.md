# Digathlon v9 — cenários novos e bichos redesenhados (21/11/2026)

Feito por cima do v8. Para usar: troque o `index.html` do jogo por este (o `dados.js` é o mesmo do v8, não mudou).

## O que mudou

**1. Superfície em 4 camadas, com profundidade**
- Céu em degraus de cor (pixel art), estrelas de 3 tamanhos piscando em ritmos diferentes, constelações, lua ou sol com halo.
- Horizonte distante (montanhas com neve, chapadas e pirâmides, vulcão): quase parado quando a câmera desce.
- Plano médio (mata em silhueta, colinas, torre de vigia, acampamento com fumaça, nuvens deslizando): anda mais.
- Primeiro plano preso ao chão: capim, flores balançando, cogumelos que brilham, pedras com musgo, cerca, placa "0 m" e a cabana da escavação com janela acesa, chaminé e lanterna balançando.
- Ao cavar, o chão sobe e vai cobrindo as camadas de trás em ritmos diferentes (paralaxe).

**2. Vida ambiente**
- Vaga-lumes, bando de pássaros ou morcegos cruzando o céu, pétalas ao vento, estrela cadente, neve em 2 camadas, cinzas e brasas, poeira do deserto — conforme o cenário.

**3. Cinco cenários**
1. Noite mística na floresta
2. Vale do amanhecer
3. Cânion do deserto
4. Pico ártico · aurora boreal
5. Vulcão cinzento

Onde escolher: botão 🌄 no canto de cima (na tela inicial) ou no ☰. O padrão é **Automático**: um cenário por dia, virando junto com a cavada do dia. A escolha fica guardada no aparelho.

**4. Toupeira e os 5 bichos antigos redesenhados (resolução dobrada)**
- Toupeira, tatu, coelho, raposa, texugo e pinguim agora têm desenho próprio, com 3 tons de sombra, no mesmo padrão dos 8 bichos do v8.
- Cada um tem a silhueta dele: toupeira gordinha de focinho rosa e garras, tatu com casco em cintas, coelho de orelhão, raposa com rabão de ponta branca, texugo com a listra no rosto, pinguim de barriga branca.
- Chapéus, roupas e acessórios continuam servindo em todos.

**5. Subsolo com profundidade**
- Raízes gigantes atravessando a terra de cima.
- Fendas escuras com caverna ao fundo (estalactites e chão lá dentro).
- Veios de minério em cada camada, que cintilam quando a luz do capacete passa perto.
- Divisa entre camadas marcada (faixa escura, pedrinhas e pingos da camada de cima).
- A faixa de cima do chão acompanha o cenário (areia, neve, cinza).

## Cuidados
- Modo acessível / "reduzir movimento": o cenário aparece, mas nada se mexe.
- Se o cenário novo der erro em algum aparelho, o jogo volta sozinho para o céu antigo em vez de travar.
- Peso: o tempo de conta do desenho (script) ficou parecido com o do v8 no teste daqui. Isso não mede a placa de vídeo nem um celular de verdade; se ficar pesado em algum aparelho, me avise.

## O que NÃO entrou (fica para a próxima)
- Fósseis, cristais, baús e ícones redesenhados em resolução dobrada (continuam como eram).
- Os blocos de terra continuam no tamanho antigo; o que ficou mais fino foi o cenário, os bichos e os detalhes novos do subsolo.

## Testes
- 177 verificações antigas (v6, v7, v8) e 24 novas do v9, em PC e celular, sem erro no console. Como a toupeira é o bicho padrão, todas elas já rodam com a toupeira redesenhada.
- A partida inteira (título, cavada, fim, compartilhar) repetida com cada um dos outros 5 bichos redesenhados (tatu, coelho, raposa, texugo, pinguim): 55 verificações, todas passando.
- Naja Party online (várias pessoas na sala): passou com os bichos novos.
- Depois do último retoque (olho do texugo) repeti só o teste do v9 e a partida com o texugo.
- Não testado em celular de verdade nem com o site no ar.
