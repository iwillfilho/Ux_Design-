---
name: priorizacao-rice
description: Gera e prioriza features ligadas a uma meta de negócio (agrupamento, RICE, matriz valor x esforço, dot voting) e fecha o trabalho no Lean UX Canvas com hipóteses e pitch de 2 minutos. Use nas etapas 7 e 8 do Exercício Dirigido.
---

# Priorização e fechamento

## 1. Features
- Meta do negócio no centro. Uma feature por post-it; agrupe por intenção (ex.: Prevenir, Desbloquear, Dar certeza).
- Cada feature deve sair de um requisito ou história (skill `requisitos-bdd`).

## 2. RICE (escalas exatas da aula)
**RICE = (A × I × C) / E**
| Fator | Escala | Pergunta |
|---|---|---|
| A, Alcance | 0 a 10 | Quantas pessoas a feature atinge? |
| I, Impacto | 1 a 3 | Quanto move a meta para cada pessoa? |
| C, Confiança | 0 a 1 | Quanta evidência temos? |
| E, Esforço | 1, 2, 3, 5, 8, 13 (Fibonacci) | Quanto custa construir? |

Mostre a conta de cada linha e ordene pelo resultado. Exemplo da aula: aviso antes do vencimento = (9 × 2 × 0,9) / 2 = 8,1.

## 3. Matriz Valor × Esforço
Quadrantes: **Fazer já** (valor alto, esforço baixo), **Projetos** (alto, alto), **Se sobrar** (baixo, baixo), **Evitar** (baixo, alto). Cada pessoa vota com 3 pontos (*dot voting*); o escopo da próxima entrega sai de RICE + votos.

## 4. Lean UX Canvas (Gothelf e Seiden, 2016)
Oito caixas na ordem: 1 Problema, 2 Resultados (negócio), 3 Usuários, 4 Benefícios (pessoa), 5 Ideias, 6 Hipóteses, 7 Aprender, 8 Experimentos.
Hipótese falsificável: "**Se** <feature>, **então** <mudança com número>, **medido por** <métrica e prazo>."

## 5. Pitch de 2 minutos
Cerca de 130 a 140 palavras por minuto, ou seja, 260 a 280 palavras, com marcas de tempo, respondendo em ordem:
1. Quem é a persona e qual o problema? 2. O que descobrimos (golfos)? 3. Quais requisitos principais? 4. Quais features priorizamos e por quê? 5. Como vamos testar?
