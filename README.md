# Quiz de Letramento Racial — IEEP

Quiz interativo baseado na **Cartilha de Letramento Racial — Conceitos, Direitos e Educação Antirracista**, do Instituto de Educação do Estado do Pará (IEEP, Belém, 2026), feito para as turmas do Ensino Médio.

**Jogue:** https://viniciusframos0.github.io/quiz-letramento-racial/

- 64 perguntas extraídas das 8 seções da cartilha
- Partidas de 10, 20 ou 30 perguntas, sem cronômetro: cada um lê no seu ritmo
- Pontuação: 100 pontos por acerto + até 50 de bônus para quem responde dentro do tempo de leitura da pergunta
- Explicação e referência à cartilha depois de cada resposta, e revisão completa no final
- Música de fundo, sons e leitura em voz alta (opcionais)

## Estrutura

```
index.html          página do quiz
perguntas.js        banco de perguntas (fácil de revisar e ampliar)
assets/             faixa, pergaminho, brasão, ícones e imagem de compartilhamento
```

Para acrescentar perguntas, edite `perguntas.js` seguindo o mesmo formato: `s` (seção), `q` (pergunta), `a` (resposta correta), `d` (três alternativas incorretas) e `e` (explicação).

## Créditos

Desenvolvimento do quiz: **Vinícius Ferreira Ramos**.
Conteúdo: Cartilha de Letramento Racial do IEEP — ficha técnica e editorial completos dentro do quiz.
