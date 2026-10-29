---
name: requisitos-bdd
description: Transforma pontos de dor em requisitos verificáveis (cadeia achado-insight-necessidade-requisito, MoSCoW) e em histórias de usuário (Cohn, INVEST) com critérios de aceite em Gherkin (Dado que/Quando/Então). Use nas etapas 5 e 6 do Exercício Dirigido.
---

# Requisitos e BDD

## 1. Cadeia de rastreio
**Achado** (fato observado) → **Insight** (o que ele revela) → **Necessidade** (o que a pessoa precisa) → **Requisito** (o que o design deve cumprir).

Um bom requisito é necessário, claro, **verificável** (número, tempo ou teste), atômico e rastreável (diga de qual golfo ou dor veio).
- Tipos: funcional, não funcional, usabilidade, acessibilidade, contexto.
- Prioridade **MoSCoW**: Must (sem isso a tarefa falha), Should (importante, tem contorno), Could (desejável), Won't (fica para depois; registre ao menos um).

## 2. História de usuário (Cohn, 2004)
"Como **<persona em situação>**, quero **<ação>**, para que **<benefício concreto>**."
Teste o "para que": se o benefício é vago ("ter boa experiência"), reescreva.

Checklist **INVEST**: Independente, Negociável, Valiosa, Estimável, Pequena (cabe numa iteração), Testável. Marque com honestidade: se depende de outra história, diga.

## 3. Critério de aceite em Gherkin (pt-BR)
```gherkin
Funcionalidade: <história>
  Cenário: <caminho principal>
    Dado que <estado inicial>
    Quando <ação da pessoa>
    Então <resultado observável, com número ou tempo>
    E <resultado adicional>
  Cenário: <exceção: falha de rede, multa, etc.>
    ...
```
Para as 2 histórias principais, escreva o caminho principal **e** pelo menos um cenário de exceção. O "Então" precisa ser verificável por quem testa.
