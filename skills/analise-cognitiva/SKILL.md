---
name: analise-cognitiva
description: Analisa a tarefa pela cabeça da persona: modelo mental, golfos de execução e avaliação (Norman), cenário em 4 movimentos (Gamestorming) e análise hierárquica de tarefas (HTA) com plano e pontos de dor. Use nas etapas 1 a 3 do Exercício Dirigido.
---

# Análise cognitiva da tarefa

## 1. Modelo mental e golfos (Norman, 1983; 2013)
- **Modelo mental**: como a pessoa *acha* que o sistema funciona. Compare os modelos da equipe e anote as diferenças (ex.: "renovar é automático" × "precisa ir ao balcão").
- **Golfo de execução** ("como eu faço?"): a pessoa sabe o que quer, mas a interface não mostra a ação. Procure: botão sem *signifier* (sinal de que é clicável e por quê), função escondida em outra aba, alvo pequeno ou fora do alcance do polegar.
- **Golfo de avaliação** ("deu certo?"): a interface não mostra o resultado. Procure: falta de confirmação, estado da rede invisível, mudança de estado sem aviso.
- Mínimo 2 itens por golfo, sempre citando um elemento concreto do caso. Justifique cada item com a heurística violada (skill `heuristicas-nielsen`) ou com uma lei de ergonomia (skill `leis-ux-ergonomia`).

## 2. Cenário (Carroll, 2000) em 4 movimentos (Gamestorming)
1. **Escolher**: persona + objetivo ("renovar o livro hoje").
2. **Situar**: onde, hora, aparelho, pressão.
3. **Narrar**: uma ação por post-it, em ordem.
4. **Provocar**: sortear um obstáculo (sem sinal, bateria baixa) e reescrever.

Entregável: parágrafo de 6 a 8 linhas, em 3ª pessoa, com obstáculo e resultado, e pelo menos 3 requisitos candidatos ("O app deve...").

## 3. HTA (Annett e Duncan, 1967)
- Objetivo no topo (`0. Renovar livro`), 3 a 5 subtarefas (`1..n`), e ações observáveis em cada uma (`1.1, 1.2`).
- **Plano 0**: regra de ordem, escolha e repetição ("faça 1 e 2; se houver multa, faça 3 antes de 4; se falhar, repita").
- **Ponto de dor**: passo que causa esforço, erro ou irritação. Circule em vermelho e diga o porquê, ligando ao golfo da etapa 1.
