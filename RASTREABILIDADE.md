# Matriz de rastreabilidade de IHC

A matriz deve ser atualizada ao longo do semestre. Ela é a principal defesa contra inconsistências entre as entregas e também registra **como o conhecimento da equipe evoluiu**. A Entrega 1 pode conter hipóteses; as entregas posteriores devem produzir evidências para sustentá-las, refutá-las ou refiná-las.

## Registro de hipóteses e lacunas da Entrega 1

Use esta tabela para itens importantes marcados como `[H]` ou `[?]`. Preserve o histórico: não apague uma hipótese refutada.

| ID | Afirmação / dúvida inicial | Tipo | Por que importa | Como/onde investigar | Evidência obtida | Estado atual | Impacto no projeto |
|---|---|---|---|---|---|---|---|
| H01 | {{...}} | H / ? | {{...}} | Entrega 2 / 3 / 7 / outra | {{link/fonte ou PENDENTE}} | aberta / sustentada / refutada / refinada | {{...}} |
| H02 | {{...}} | H / ? | {{...}} | {{...}} | {{...}} | aberta | {{...}} |

## Rastreabilidade entre artefatos

| ID | Necessidade/problema | Persona | Cenário problema | Objetivo/tarefa | HTA/GOMS/CTT | Cenário de interação / signos | MoLIC | Tela(s) Figma | Heurística / problema | Tarefa no teste de usuário | Decisão/melhoria |
|---|---|---|---|---|---|---|---|---|---|---|---|
| R01 | {{...}} | {{P01}} | {{C01}} | {{T01}} | {{links}} | {{...}} | {{link}} | {{telas}} | {{H# ou —}} | {{UT01}} | {{...}} |
| R02 |  |  |  |  |  |  |  |  |  |  |  |

## Como usar

- Use identificadores estáveis (`H01`, `P01`, `C01`, `T01`, `M01`, `UT01`).
- Quando uma necessidade/problema tiver origem em uma hipótese da Entrega 1, cite o ID correspondente (`H01`, `H02`...).
- Uma linha pode se desdobrar em mais de uma quando um objetivo possui múltiplos caminhos.
- Não force uma relação inexistente: se algo ainda não foi modelado, marque `PENDENTE`.
- Ao remover uma funcionalidade, registre a decisão em vez de apagar silenciosamente o histórico.
