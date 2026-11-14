# Cara a Cara da Química 🧪

Um jogo interativo de adivinhação e dedução química inspirado no clássico "Cara a Cara" (Guess Who?), desenvolvido em um único arquivo HTML standalone, sem dependências externas pesadas e com visual dark moderno.

## 🚀 Modos de Jogo

1. **Modo Local (vs CPU)**:
   - Jogue contra o computador.
   - Oponente inteligente com algoritmo de dedução por busca binária que escolhe perguntas que eliminam o maior número de possibilidades a cada rodada.

2. **Modo Online (Multijogador em Tempo Real)**:
   - Sincronização em tempo real via **Firebase Realtime Database**.
   - Crie uma sala com código de 6 caracteres ou compartilhe o link direto (`?room=CODIGO`).
   - Sincronização automática de turnos, perguntas, respostas e palpites.

---

## 🔬 Elementos Químicos (30 Elementos)
O tabuleiro conta com 30 elementos químicos fundamentais:
`H`, `He`, `Li`, `C`, `N`, `O`, `F`, `Ne`, `Na`, `Mg`, `Al`, `Si`, `P`, `S`, `Cl`, `Ar`, `K`, `Ca`, `Fe`, `Cu`, `Zn`, `Br`, `Ag`, `I`, `Ba`, `Au`, `Hg`, `Pb`, `U`, `Kr`.

---

## ❓ 30 Perguntas Pré-Definidas (Sem Repetição)
O jogo possui 30 perguntas químicas, geológicas e industriais. Uma vez utilizada por qualquer um dos jogadores, a pergunta é desativada permanentemente durante a partida:

1. Ocorre naturalmente na Terra?
2. É um metal?
3. É um não-metal?
4. É um semimetal?
5. É um gás nobre?
6. É um metal de transição?
7. Pertence ao grupo 1 ou 2?
8. Está no período 1, 2 ou 3?
9. Tem mais de 20 prótons?
10. Sua massa atômica é maior que 50?
11. É sólido à temperatura ambiente?
12. É líquido à temperatura ambiente?
13. É gasoso à temperatura ambiente?
14. É encontrado no ar atmosférico?
15. É encontrado no mar ou na água do mar?
16. É encontrado no corpo humano?
17. É radioativo?
18. Reage com água?
19. Tem propriedades magnéticas?
20. É extraído de minérios metálicos?
21. É um dos elementos mais abundantes na crosta terrestre?
22. É usado em construção civil?
23. É usado em eletrônicos ou tecnologia?
24. É usado em embalagens ou utensílios domésticos?
25. É usado como combustível ou fonte de energia?
26. É usado em baterias ou pilhas?
27. É usado na medicina ou farmácia?
28. Tem alguma aplicação na indústria alimentícia?
29. Faz parte da composição do sal de cozinha ou fertilizantes?
30. É usado na fabricação de lâmpadas ou iluminação?

---

## 🛠️ Tecnologias
- **HTML5 / CSS3 / JavaScript (Vanilla)**
- **Firebase Realtime Database (CDN compat v10.12.0)**
- Totalmente executável apenas abrindo o arquivo `index.html` no navegador.

