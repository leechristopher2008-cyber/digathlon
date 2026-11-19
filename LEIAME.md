# Digathlon

Jogo de cavar com respostas: quanto mais rara a resposta, mais fundo a toupeira cava.
Abre pelo GitHub Pages: `index.html` + `dados.js` (perguntas e respostas).

## Modos

**Sozinho**
- **Cavada do dia**: 7 perguntas, iguais pra todo mundo no dia.
- **Cavada livre**: sem vidas; errar não custa nada; pode pular à vontade. A partir da 7ª pergunta, de vez em quando volta uma que já saiu (marcada "↻ VOLTOU"), e a resposta que você já usou nela não vale de novo.
- **Competitivo**: 3 ❤ e 3 pulos. Errou = −1 ❤. Acabou o tempo = fim de jogo. Guarda o recorde.
- **Roda da toca**: festa num celular só, passando de mão em mão.

**Online (cada um no seu celular, o líder escolhe o modo e o tempo)**
- **🐍 Naja Party**: passa a naja com uma resposta antes do bote. Com vidas: quem leva todos os botes sai; o último que sobra ganha.
- **🏁 Corrida** (1, 2, 3 ou 5 min): todo mundo recebe as mesmas perguntas e cava no seu ritmo; errar tira ❤ (se tiver vidas); 3 pulos; ganha quem estiver mais fundo.
- **⚡ Velocidade · só o primeiro pontua**: pergunta de resposta única (contas, capitais, símbolos químicos, siglas de estados); só quem acerta primeiro ganha ponto.
- **⚡ Velocidade · ranking**: todo mundo responde; pontua pela ordem (1º ganha mais).

No fim de cada partida online aparece o vencedor e o líder tem o botão "jogar de novo".

## Firebase (modo online)

Caminhos usados em `rooms/CÓDIGO`:
- `meta` (líder, estado, vidas) e `game` (a partida): só o líder escreve.
- `players/ID` e `live/ID`: cada um só escreve o seu.
  A corrida grava em `live/ID/c` e a velocidade em `live/ID/vl`, marcados com o id da partida, então ninguém apaga a pasta dos outros.

Regras sugeridas: `database.rules.json` (cole em Firebase Console → Realtime Database → Regras → Publicar).
Se as regras atuais forem as de "modo de teste", elas expiram sozinhas depois de uns 30 dias e o online para de funcionar.
