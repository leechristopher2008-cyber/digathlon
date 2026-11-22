# TOUPIX v10 — parte 1 (22/11/2026)

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

## Ainda não entrou (parte 2)
Animação de cavar e túnel irregular, subida com corda, abertura animada, bicho se mexendo na tela inicial, animações do guarda-roupa, camadas mais ricas com recompensa, fósseis/cristais/baús redesenhados, perfil e sequência salvos na nuvem.
