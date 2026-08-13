# Entrega 1 — Conhecendo o projeto, o usuário e o problema

**Data:** {{dd/mm/aaaa}}  
**Status:** ⬜ não iniciada  
**Responsabilidade:** 1 solução consolidada por equipe

## Objetivo da atividade

Reinterpretar o tema de TCC sob a perspectiva de Interação Humano-Computador. Nesta primeira atividade, a equipe **não deve começar desenhando telas nem defendendo uma solução tecnológica**. O objetivo é compreender quem são as pessoas envolvidas, o que elas desejam realizar, quais problemas enfrentam, em que contexto esses problemas acontecem e quais alternativas já utilizam.

Ao final desta entrega, a equipe deve conseguir diferenciar:

- **objetivo do projeto** de **objetivo do usuário**;
- **problema do usuário** de **solução tecnológica**;
- **fato conhecido** de **hipótese ainda não investigada**;
- **funcionalidade do sistema** de **atividade/resultado que o usuário precisa alcançar**;
- **usuário direto** de outros stakeholders afetados pelo produto.

> **Regra da primeira semana:** não é necessário saber todas as respostas. Quando a equipe ainda não souber, registre explicitamente a incerteza. Uma hipótese identificada é melhor do que uma suposição apresentada como fato.

## Como classificar as respostas

Sempre que a resposta fizer uma afirmação sobre **usuários, problemas, atividades, necessidades, contexto ou mercado**, use um dos marcadores:

- **[F] Fato conhecido** — existe alguma evidência ou fonte que sustenta a afirmação.
- **[H] Hipótese** — a equipe acredita que seja verdadeiro, mas ainda precisa investigar.
- **[?] Não sabemos ainda** — informação importante que deverá ser descoberta posteriormente.

Quando usar **[F]**, informe a origem da evidência: TCC, literatura, documento, observação, entrevista anterior, dado institucional, experiência profissional documentada etc. Quando uma hipótese ou lacuna for importante para o projeto, atribua um identificador (`H01`, `H02`...) e registre-a também em [`../RASTREABILIDADE.md`](../RASTREABILIDADE.md).

**Exemplo:**

> **[H] H01 — Professores preferem registrar presença pelo celular durante a aula.**  
> Evidência atual: ainda não existe. Hipótese a investigar com usuários.

---

## 0. Identificação do projeto

### 0.1 Membros da equipe

| Nome completo | Matrícula | GitHub |
|---|---:|---|
| {{...}} | {{...}} | {{...}} |

### 0.2 Título atual do TCC/projeto

{{...}}

### 0.3 Orientador(a)

{{...}}

### 0.4 Produto atualmente previsto no TCC

Descreva apenas o que já está previsto formalmente no TCC, sem transformar esta resposta em justificativa de design.

{{...}}

---

## 1. Entendendo o projeto

### 1.1 Explique o projeto em **uma frase**, sem mencionar linguagem de programação, framework ou banco de dados.

{{...}}

### 1.2 Qual situação, atividade ou problema do mundo real motivou esse projeto?

{{[F/H/?] ...}}

### 1.3 O que o projeto pretende mudar ou melhorar no mundo real?

Evite responder apenas “desenvolver um sistema”, “criar um aplicativo” ou equivalente.

{{...}}

### 1.4 O que se espera que esteja diferente **para as pessoas** quando o projeto estiver concluído?

{{[F/H/?] ...}}

---

## 2. Entendendo as pessoas envolvidas

### 2.1 Quem deverá **interagir diretamente** com o produto ou sistema?

{{[F/H/?] ...}}

### 2.2 Existem tipos diferentes de usuários diretos? Quais?

| Tipo de usuário | O que faz / por que interage | Status | Evidência atual |
|---|---|---|---|
| {{...}} | {{...}} | F / H / ? | {{...}} |

### 2.3 Existem pessoas que não usam diretamente o sistema, mas são afetadas por ele, fornecem informações, supervisionam atividades ou tomam decisões? Quem?

| Stakeholder | Relação com o projeto | Usa a interface diretamente? | Status/evidência |
|---|---|---|---|
| {{...}} | {{...}} | sim / não | {{...}} |

### 2.4 Que características desses usuários podem influenciar a interação?

Considere apenas características relevantes: conhecimento do domínio, experiência tecnológica, frequência de uso, idade quando pertinente, alfabetização digital, limitações funcionais, acessibilidade, idioma, experiência profissional etc.

{{[F/H/?] ...}}

---

## 3. Entendendo os objetivos e atividades dos usuários

### 3.1 O que o usuário está tentando **conseguir no mundo real** quando utiliza ou utilizaria esse produto?

> Pense em resultados do usuário, não em comandos da interface.

{{[F/H/?] ...}}

### 3.2 Quais são as três atividades mais importantes que esse usuário precisa realizar?

| ID | Atividade/objetivo do usuário | Quem realiza | Status/evidência |
|---|---|---|---|
| A01 | {{...}} | {{...}} | {{...}} |
| A02 | {{...}} | {{...}} | {{...}} |
| A03 | {{...}} | {{...}} | {{...}} |

### 3.3 Dessas atividades, qual parece ser a mais frequente? Por quê?

{{[F/H/?] ...}}

### 3.4 Qual parece ser a mais importante ou crítica? O que torna essa atividade crítica?

{{[F/H/?] ...}}

---

## 4. Entendendo o problema atual

### 4.1 Como o usuário realiza essas atividades **hoje**, antes da solução proposta pelo TCC?

Descreva o processo atual: sistemas, papel, planilhas, aplicativos, mensagens, memória, atendimento humano, improvisos ou outras estratégias.

{{[F/H/?] ...}}

### 4.2 O que atualmente é difícil, demorado, confuso, repetitivo, arriscado ou desagradável?

{{[F/H/?] ...}}

### 4.3 O que acontece quando o usuário não consegue realizar adequadamente essa atividade?

Considere retrabalho, perda de tempo, erro, risco, frustração, custo, atraso, impacto em outras pessoas etc.

{{[F/H/?] ...}}

### 4.4 Conte **uma situação concreta** em que uma pessoa enfrenta esse problema.

Escreva uma pequena narrativa contendo pessoa, objetivo, atividade, contexto, dificuldade e consequência. **Não descreva a futura solução.** Este relato poderá ser aprofundado posteriormente na Entrega 4.

{{[F/H/?] narrativa...}}

### 4.5 Que evidência a equipe possui hoje de que esse problema realmente existe?

| Evidência/fonte | O que ela sustenta | Limitação da evidência |
|---|---|---|
| {{...}} | {{...}} | {{...}} |

Se ainda não houver evidência, registre a afirmação como hipótese e explique como poderá ser investigada.

---

## 5. Entendendo o contexto de uso

### 5.1 Onde e em quais situações o produto provavelmente será utilizado?

{{[F/H/?] ...}}

### 5.2 Em quais dispositivos, equipamentos ou meios deverá ocorrer a interação?

{{[F/H/?] ...}}

### 5.3 Existem condições do ambiente físico que podem afetar o uso?

Considere, quando pertinente: iluminação, ruído, mobilidade, conexão, privacidade, uso com uma mão, pressa, interrupções, equipamentos compartilhados e espaço disponível.

{{[F/H/?] ...}}

### 5.4 Existem fatores sociais ou organizacionais envolvidos?

Considere outras pessoas presentes, colaboração, chefias, políticas, regras institucionais, responsabilidade profissional, necessidade de autorização, turnos, papéis e relações de poder.

{{[F/H/?] ...}}

### 5.5 Um erro do usuário pode produzir alguma consequência relevante? Qual?

{{[F/H/?] ...}}

---

## 6. Entendendo o que já existe

> Nesta primeira entrega não é necessário realizar ainda a análise aprofundada de concorrência. O objetivo é construir um **mapa inicial** que será investigado sistematicamente na Entrega 2.

### 6.1 Como as pessoas resolvem o problema atualmente?

Liste ferramentas, sistemas, planilhas, sites, aplicativos, papel, WhatsApp, processos manuais ou outras alternativas.

| Alternativa atual | Quem usa | Para qual atividade | Status/evidência |
|---|---|---|---|
| {{...}} | {{...}} | {{...}} | {{...}} |

### 6.2 Existem produtos que atuam na mesma área, mesmo que não façam exatamente a mesma coisa que o TCC?

{{[F/H/?] ...}}

### 6.3 O que essas soluções existentes parecem fazer bem?

{{[F/H/?] ...}}

### 6.4 O que elas parecem fazer mal, dificultar ou não atender?

{{[F/H/?] ...}}

### 6.5 Existem padrões de interface, vocabulário ou formas de trabalho que esse público já parece conhecer?

{{[F/H/?] ...}}

---

## 7. Voltando para a proposta do TCC

Somente depois de refletir sobre usuários, objetivos, problema, contexto e alternativas existentes, retome a solução prevista no TCC.

### 7.1 Qual benefício concreto o projeto pretende oferecer ao usuário?

| Benefício esperado | Problema/necessidade associada | Usuário beneficiado | Status/evidência |
|---|---|---|---|
| {{...}} | {{...}} | {{...}} | {{...}} |

### 7.2 Que ações o usuário deverá conseguir realizar através da futura interface?

Escreva em linguagem de usuário, evitando detalhes de backend.

| ID | O usuário precisa conseguir... | Para alcançar... | Prioridade inicial |
|---|---|---|---|
| F01 | {{ação/capacidade}} | {{objetivo}} | alta / média / baixa |

### 7.3 Para cada ação principal, complete a frase:

> **“O usuário precisa conseguir `{{ação}}` para alcançar `{{objetivo}}`.”**

{{...}}

### 7.4 O projeto realmente precisa de uma interface com usuário? Se sim, onde ocorre a interação?

- [ ] Sim
- [ ] Não
- [ ] Ainda precisa ser esclarecido

**Justificativa:** {{...}}

### 7.5 Há alguma decisão tecnológica do TCC já definida que possa limitar ou influenciar a interação?

A tecnologia aparece **somente agora**, depois da compreensão inicial do uso.

| Tecnologia/restrição já definida | Por que existe | Possível impacto na interação |
|---|---|---|
| {{...}} | {{...}} | {{...}} |

### 7.6 Quais são hoje as **três maiores dúvidas da equipe** sobre usuários, problema ou contexto de uso?

| ID | Dúvida/hipótese prioritária | Por que importa | Em qual entrega poderá ser investigada |
|---|---|---|---|
| H01 | {{...}} | {{...}} | Entrega 2 / 3 / 7 / outra |
| H02 | {{...}} | {{...}} | {{...}} |
| H03 | {{...}} | {{...}} | {{...}} |

Registre essas hipóteses também na seção correspondente de [`../RASTREABILIDADE.md`](../RASTREABILIDADE.md).

---

## 8. Síntese inicial da equipe

Complete a síntese em linguagem curta e concreta.

| Pergunta | Síntese atual |
|---|---|
| Quem são os principais usuários? | {{...}} |
| O que eles precisam alcançar? | {{...}} |
| Qual é o principal problema atual? | {{...}} |
| Como resolvem isso hoje? | {{...}} |
| Em qual contexto o problema ocorre? | {{...}} |
| Que consequência o problema produz? | {{...}} |
| Qual benefício o TCC pretende oferecer? | {{...}} |
| Quais pontos ainda são hipóteses? | {{H01, H02...}} |

### Delimitação inicial

**Dentro do escopo:** {{...}}  
**Fora do escopo:** {{...}}

---

## 9. Como esta entrega alimenta as próximas

- **Entrega 2 — Análise de concorrência:** aprofunda as alternativas, produtos e padrões identificados inicialmente aqui.
- **Entrega 3 — Personas/contexto/jornada:** detalha e organiza os perfis e características de usuários inicialmente levantados.
- **Entrega 4 — Cenários de problema:** transforma situações concretas desta entrega em narrativas mais completas e refinadas.
- **Entrega 5 — Análise de tarefas:** aprofunda as atividades importantes identificadas aqui e nos cenários.
- **Entrega 7 — Coleta de dados:** transforma hipóteses e lacunas `[H]`/`[?]` em perguntas de investigação com usuários.

A Entrega 1 é uma **fotografia inicial do conhecimento da equipe**. Ela poderá ser corrigida ao longo do semestre quando novas evidências aparecerem; não apague a hipótese original sem registrar o que foi aprendido.

## Checklist de qualidade

- [ ] A equipe descreveu o projeto sem começar pela tecnologia.
- [ ] Está clara a diferença entre objetivo do TCC e objetivo do usuário.
- [ ] Usuários diretos e stakeholders foram diferenciados.
- [ ] As atividades principais foram descritas como objetivos/ações do usuário, não como botões ou telas.
- [ ] O processo atual foi descrito antes da solução proposta.
- [ ] Existe pelo menos uma situação concreta mostrando o problema em contexto.
- [ ] Problema e solução não foram confundidos.
- [ ] O contexto inclui ambiente físico, social/organizacional, dispositivos e consequências de erro quando pertinentes.
- [ ] A equipe registrou como o problema é resolvido hoje e quais alternativas já existem.
- [ ] Afirmações sobre usuários/problemas/contexto estão marcadas como `[F]`, `[H]` ou `[?]` quando necessário.
- [ ] Fatos importantes possuem alguma evidência/fonte identificada.
- [ ] Hipóteses prioritárias receberam IDs (`H01`, `H02`...) e foram registradas na rastreabilidade.
- [ ] Tecnologias aparecem como restrições/decisões do TCC, e não como justificativa automática da solução.
- [ ] As três principais dúvidas da equipe estão explícitas.
