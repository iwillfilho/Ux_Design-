---
name: ficha-latex
description: Gera uma nova ficha de análise de software no formato LaTeX de Entrega_final/UX_final.tex (macros \ficha, tabela, \linha, \secao, \melhoria). Use para adicionar um novo aplicativo ao relatório.
---

# Nova ficha em LaTeX

Copie o bloco de uma ficha existente em `Entrega_final/UX_final.tex` e troque o conteúdo:

1. `\ficha{FICHA N --- SOFTWARE X: NOME}{Subtítulo}`
2. Ambiente `tabela` com: Software escolhido, Tarefa, Persona, Contexto, Critério de sucesso.
3. Ambiente `tabela` com `\secao{PRINCÍPIOS DE INTERAÇÃO E ERGONOMIA DIGITAL}` (5 linhas, ver skill leis-ux-ergonomia).
4. Ambiente `tabela` com `\secao{COLMEIA DA EXPERIÊNCIA DE MORVILLE (2004)}` (7 linhas, ver skill colmeia-morville).
5. `\melhoria{... \metrica{} ...}`
6. `\newpage` entre fichas.

Compile com `latexmk -pdf -interaction=nonstopmode UX_final.tex` e confira o PDF (uma ficha por página).
