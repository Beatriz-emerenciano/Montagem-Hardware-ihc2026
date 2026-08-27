# Entrega 1 — Conhecendo o projeto, o usuário e o problema

**Data:** 13/08/2026
**Status:** 🟨 Em andamento 
**Responsabilidade:** 1 solução consolidada por equipe

## Objetivo da atividade

Reinterpretar o tema do TCC sob a perspectiva de Interação Humano-Computador e construir um **entendimento comum entre os integrantes da equipe**.

A disciplina utiliza preferencialmente o tema do TCC para os exercícios de IHC. Isso vale tanto para TCCs que já preveem uma interface quanto para trabalhos cujo resultado principal é algoritmo, modelo, API, biblioteca, análise de dados, infraestrutura, estudo experimental ou outro artefato técnico.

> **Importante:** a interface projetada na disciplina é um artefato de aprendizagem de IHC. Ela **não se torna automaticamente uma obrigação do TCC**. Sua incorporação ao trabalho de conclusão depende de decisão da equipe e do orientador.

Antes de preencher, leia [`../GUIA_ESCOPO_IHC.md`](../GUIA_ESCOPO_IHC.md).

Nesta primeira semana a equipe **não deve começar desenhando telas**. Primeiro deverá compreender:

- o que o TCC realmente produz;
- quem poderia obter valor dessa contribuição;
- quais pessoas interagem, administram, configuram, interpretam ou são afetadas;
- o que essas pessoas precisam alcançar;
- como atividades relacionadas acontecem hoje;
- problemas, limitações e contexto;
- alternativas existentes;
- qual recorte de interação fará sentido para a disciplina.

Ao final desta entrega, a equipe deve diferenciar:

- **tema do TCC** × **escopo formal do TCC** × **escopo de IHC da disciplina**;
- **objetivo do projeto** × **objetivo do usuário**;
- **problema do usuário** × **solução tecnológica**;
- **fato conhecido** × **hipótese** × **lacuna de conhecimento**;
- **capacidade técnica** × **forma de uso dessa capacidade**;
- **funcionalidade** × **atividade/resultado que o usuário precisa alcançar**;
- **usuário direto** × **stakeholders**.

---

## Como classificar as respostas

Sempre que a resposta fizer uma afirmação sobre usuários, problemas, atividades, necessidades, contexto ou mercado, use:

- **[F] Fato conhecido** — existe evidência/fonte.
- **[H] Hipótese** — afirmação plausível que ainda precisa ser investigada.
- **[?] Não sabemos ainda** — lacuna relevante.

Quando usar `[F]`, informe a origem. Hipóteses prioritárias devem receber IDs (`H01`, `H02`...) e também ser registradas em [`../RASTREABILIDADE.md`](../RASTREABILIDADE.md).

> **Exemplo:** `[H] H01 — DBAs considerariam útil comparar automaticamente o plano atual de execução com uma recomendação produzida pelo algoritmo.`

Uma hipótese explicitada é melhor do que uma suposição escondida.

---

# 0. Identificação do TCC e da equipe

## 0.1 Membros

| Nome completo | Matrícula | GitHub | 

| Beatriz Cristina Emerenciano| 22.222041-0 | Beatriz-emerenciano |

|Larissa Santos Fiuza|22.123.042-8|LarissaFiuza7

## 0.2 Título atual do TCC

 Desenvolvimento de um jogo sério e estudo experimental de abordagens combinadas para ensino de montagme de hardware.

## 0.3 Orientador(a)

Rafael Gomes Alves

## 0.4 Qual é o resultado principal atualmente previsto no TCC?

Marque e descreva:

- [x] sistema/aplicação interativa;
- [ ] algoritmo;
- [ ] modelo de IA/ML/LLM;
- [ ] biblioteca/API/framework;
- [ ] análise de dataset;
- [x] estudo/benchmark/avaliação experimental;
- [ ] infraestrutura/backend;
- [ ] componente embarcado/IoT;
- [ ] outro: {{...}}.

**Descrição:** 
Estudo experimental de abordagens combinadas sendo jogo sério e tutorial para ensino da montagem de hardware.

## 0.5 O TCC já previa desenvolvimento de interface com usuário?

- [x] Sim, a interface já faz parte do TCC.
- [ ] Parcialmente; existe alguma interação, mas ainda não está bem definida.
- [ ] Não. O TCC é predominantemente técnico e não previa interface.

**Explique o que está formalmente previsto no TCC:** Desenvolver um jogo sério e a partir disto realizar um estudo experimental  de abordagen de ensino voltadas para montagem de hardware.

> Esta resposta serve para separar o compromisso do TCC do projeto da disciplina. Mesmo quando a opção for **não**, a equipe irá definir uma interface para exercitar IHC.

# 1. Entendendo a contribuição do projeto

## 1.1 Explique o TCC em uma frase, sem citar linguagem de programação, framework ou banco de dados.

Desenvolvimento de um jogo sério e estudo experimental de abordagens de aprendizado.

## 1.2 Qual situação, atividade ou problema do mundo real motivou o TCC?

[H] H01 - Muitas pessoas não sabem ou conseguem identificar corretamente as peças de um computador nem compreender a ordem e a forma correta de montagem, o que dificulta o aprendizado e aumenta a chance de erros durante o processo.

## 1.3 Qual é a **capacidade/contribuição central** produzida pelo TCC?

Nosso TCC propõe, o desenvolvimento de um jogo sério para aprendizado e treinamento de reconhecimento de componentes e montagem de hardware, o sistema permite o usuário identificar, explorar e compreender os principais componentes de um computador, além de realizar a montagem atravém de uma plataforma de jogo e/ou combinada com tutorial. A solução visa democratizar o acesso ao conhecimento técnico, antendendo desde iniciantes até aqueles que buscam consolidar conhecimentos básicos de forma prática e inovadora e compreender qual a melhor abordagem para absorver este conhecimento.

## 1.4 O que se espera que esteja diferente **para pessoas, organizações ou processos** se essa contribuição for bem-sucedida?

[H] H02 - A abordagem de aprendizado.

## 1.5 O que é mérito técnico/científico do TCC e o que seria uma possível aplicação prática?

| Mérito/contribuição técnica | Possível aplicação/valor em uso |

 A contribuição visa democratizar o acesso ao conhecimento técnico, antendendo desde iniciantes até aqueles que buscam consolidar conhecimentos básicos de forma prática e inovadora através do desenvolvimento e avaliação de um Serious Game Web 3D voltado ao ensino de conceitos e procedimentos básicos de montagem de computadores, utilizando recursos de computação gráfica e gamificação para promover aprendizagem interativa.


# 2. Entendendo as pessoas envolvidas

## 2.1 Quem interage diretamente com o produto, se já existe interface prevista? - 
[H] H02 - O usuário final - aquele que quer aprender.


## 2.2 Quem poderia **usar, configurar, administrar, operar, interpretar ou tomar decisões** a partir da contribuição técnica?

Considere perfis profissionais e stakeholders, não apenas consumidores finais.

| Perfil | Relação com a contribuição | O que faria | Status/evidência |
|---|---|---|---|
| {{DBA / analista / gestor / técnico / pesquisador / usuário final...}} | {{...}} | {{...}} | F / H / ? |

Estudante aluno| usuário final e principal beneficiário|Utilizaria o Serious Game para aprender conceitos de hardware, identificar componentes e praticar virtualmente a montagem de computadores|f - público-alvo definido|
Instrutor de iformática| usuário educacional indireto|Poderia utilizar o jogo como recurso complementar às aulas e atividades práticas de hardware|H - possível aplicação|
Professor responsável pela pela disciplina| steakholders educacional|Poderia interpretar o desempenho dos alunos e utilizar os resultados para identificar dificuldades de aprendizagem|H - depende da implementação de recursos de acompanhamento|
Instituição de ensino|Stakeholder institucional|Poderia disponibilizar o Serious Game como ferramenta complementar para disciplinas ou cursos relacionados a informática e hardware|H possível aplicação|
Pesquisador da área de tecnologia|Usuário dos resultados da contribuição científica|Poderia analisar os resultados obtidos na avaliação do Serious Game e utilizá-los como referência para pesquisas futuras|H -aplicação acadêmica possível|
Equipe desenvolvedora|Administrador/configurador do sistema|Configuraria conteúdos, fases, componentes, regras e elementos do jogo|F - responsabilidade da equipe no desenvolvimento|



## 2.3 Existem pessoas afetadas que não usariam a interface diretamente?

| Stakeholder | Como é afetado | Usa interface? | Status/evidência |
|---|---|---|---|
| {{...}} | {{...}} | sim/não | {{...}} |

Professores | Podem fornecer a interface para alunos para auxílio no estudo| sim/não, não é necessário mas pode utilizar para demonstração | 

## 2.4 Que características desses perfis podem influenciar a interação?

Considere conhecimento do domínio, experiência tecnológica, frequência de uso, necessidades de acessibilidade, responsabilidade profissional, familiaridade com métricas, linguagem técnica, urgência etc.

{{[F/H/?] ...}}

 [H] -  Aluno  Podem ser beneficiados futuramente pela disponibilização do jogo como ferramenta de aprendizagem. 
 [H] - Professor pode utilizar o jogo como recurso complementar ao ensino e como apoio às atividades práticas.
[H] -Instituição de ensino Pode incorporar a ferramenta como recurso educacional complementar e reduzir a necessidade de equipamentos físicos para determinadas atividades introdutória.
[H] - Pesquisadores podem utilizar e interpretar os resultados da avaliação para pesquisas relacionadas a Serious Games, educação e tecnologia. 
[H] - Instrutor de informática poderia utilizar o jogo como recurso complementar às aulas e atividades práticas de hardware

# 3. Entendendo objetivos e atividades

## 3.1 O que o usuário está tentando conseguir no mundo real?

Não responda “usar o algoritmo”, “clicar no sistema” ou “ver o dashboard”.

{{[F/H/?] ...}}

## 3.2 Quais são as atividades mais importantes?

| ID | Atividade/objetivo | Quem realiza | Frequência/criticidade inicial | Status/evidência |
|---|---|---|---|---|
| A01 | {{Acessar o Serious Game e iniciar uma atividade}} | {{Estudante}} | {{alta}} | {{f}} |
| A02 | {{Consultar o tutorial e aprender sobre os componentes de hardware}} | {{estudante}} | {{alta}} | {{f}} |
| A03 | {{Identificar componentes de um computador}} | {{estudante}} | {{alta}} | {{f}} |
| A04 | {{Consultar informações sobre a função de cada componente}} | {{estudante}} | {{média}} | {{f}} |
| A05 | {{Selecionar ou arrastar o componente para o local correto}} | {{estudante}} | {{alta}} | {{f}} |
| A06 | {{Realizar as etapas de montagem virtual do computador}} | {{estudante}} | {{alta}} | {{f}} |
| A07 | {{Receber feedback sobre acertos e erros durante a montagem}} | {{estudante}} | {{média/alta}} | {{f}} |
| A08 | {{Completar desafios e fases com diferentes níveis de dificuldade}} | {{estudante}} | {{média/alta}} | {{f}} |
| A09 | {{Consultar pontuação e progresso no jogo}} | {{estudante}} | {{média}} | {{h}} |
| A10 | {{Repetir atividades para melhorar o desempenho e reforçar o aprendizado}} | {{estudante}} | {{média}} | {{h}} |
| A11 | {{Avaliar o conhecimento antes e depois da utilização do jogo}} | {{Pesquisador/equipe do TCC}} | {{alta}} | {{f}} |
| A12 | {{Analisar os resultados obtidos pelos participantes durante a avaliação}} | {{Equipe do TCC}} | {{alta}} | {{f}} |




## 3.3 Qual atividade parece mais frequente? Por quê?

{{[F/H/?] ...}}

[f] A02 - Tutorial
[f]A03 - Identificação
[f]A05-  Localização do componente
[f]A06 - Montagem virtual
[f]A07 - Feedback
[f]A09- Progresso.

## 3.4 Qual parece mais crítica? Que consequência existe se for mal executada?

{{[F/H/?] ...}}

[F] Atualmente, o aprendizado sobre identificação e montagem de componentes de computadores pode ser realizado por meio de aulas teóricas, materiais didáticos, vídeos, manuais, tutoriais online e atividades práticas com equipamentos físicos. Durante atividades presenciais, o estudante pode receber orientações de professores ou instrutores e manipular diretamente os componentes para compreender sua função e forma de instalação.
[F] Também existem conteúdos e tutoriais digitais que apresentam os componentes e demonstram procedimentos de montagem, geralmente por meio de textos, imagens e vídeos.
[H] Entretanto, esses métodos podem apresentar limitações quanto à possibilidade de o estudante praticar repetidamente e de forma interativa, especialmente quando não há disponibilidade de equipamentos físicos ou acompanhamento imediato durante a atividade.
[H] O Serious Game proposto busca atuar como uma ferramenta complementar a esses métodos, permitindo a prática virtual, a repetição das atividades e o recebimento de feedback durante a realização das etapas de montagem.

# 4. Entendendo o problema ou processo atual

## 4.1 Como essas atividades são realizadas hoje, antes da interface imaginada na disciplina?

Pode existir software concorrente, linha de comando, planilha, notebook, script, painel técnico, processo manual, consulta a logs, análise visual, troca de mensagens, decisão por especialista etc.

{{[F/H/?] ...}}

[F] Atualmente, o aprendizado sobre identificação e montagem de componentes de computadores pode ser realizado por meio de aulas teóricas, materiais didáticos, vídeos, manuais, tutoriais online e atividades práticas com equipamentos físicos. Durante atividades presenciais, o estudante pode receber orientações de professores ou instrutores e manipular diretamente os componentes para compreender sua função e forma de instalação.
[F] Também existem conteúdos e tutoriais digitais (Softawares) que apresentam os componentes e demonstram procedimentos de montagem por meio de gamificação.

## 4.2 O que é difícil, demorado, confuso, repetitivo, arriscado ou pouco transparente?

{{[F/H/?] ...}}

[F] Para estudantes iniciantes, pode ser difícil identificar corretamente os componentes de um computador e compreender a função de cada peça, principalmente quando os componentes possuem aparência semelhante ou diferentes modelos.

[F] Também pode ser difícil compreender a ordem de montagem e identificar corretamente onde cada componente deve ser instalado. A aprendizagem prática depende, muitas vezes, da disponibilidade de equipamentos físicos e da orientação de um professor ou pessoa com conhecimento técnico.

[H] A repetição da montagem pode ser limitada pela quantidade de equipamentos disponíveis e pelo tempo destinado às atividades práticas.

[H] A ausência de feedback imediato durante uma atividade realizada de forma autônoma pode dificultar a identificação e correção de erros pelo estudante.

[F] A tecnologia necessária para colocar em prática a proposta envolve o desenvolvimento de uma aplicação web interativa, utilizando recursos de programação, computação gráfica e modelos tridimensionais.

## 4.3 Que informações o profissional precisa interpretar para tomar decisão?

{{[F/H/?] ...}}
[F] O estudante precisa interpretar informações relacionadas à identificação dos componentes, suas funções, características básicas, compatibilidade e local de instalação na placa-mãe.

[F] Durante a montagem, também precisa compreender a sequência adequada das etapas e reconhecer os locais correspondentes a cada componente.

[H] O estudante pode utilizar essas informações para decidir qual componente deve ser instalado, onde deve ser colocado e qual procedimento deve ser realizado em cada etapa da montagem.

## 4.4 O que acontece quando a atividade falha ou quando o resultado é interpretado incorretamente?

{{[F/H/?] ...}}
[F] Quando um estudante identifica incorretamente um componente ou interpreta de forma equivocada as instruções de montagem, pode realizar uma etapa incorreta ou instalar um componente em um local inadequado.

[F] Em uma atividade prática com equipamentos reais, um procedimento inadequado pode resultar em danos aos componentes dependendo do procedimento realizado.", além de exigir a intervenção de um professor ou técnico para identificar e corrigir o erro.

[H] No contexto educacional, a repetição de procedimentos incorretos sem feedback adequado pode contribuir para a consolidação de conhecimentos equivocados e dificultar o aprendizado posterior.

[F] Além disso, erros durante atividades práticas podem gerar insegurança no estudante e aumentar a necessidade de acompanhamento por parte do professor ou instrutor.

## 4.5 Conte uma situação concreta.

Escreva uma pequena narrativa com pessoa, objetivo, atividade, contexto, dificuldade e consequência. **Não descreva ainda a futura solução.**

{{[F/H/?] narrativa...}}
[H] Um estudante iniciante que recentemente comprou um hardware e quer montar um computador durante uma aula prática de hardware. Ele identifica corretamente a memória RAM, mas possui dúvidas sobre quais slots da placa-mãe devem ser utilizados e sobre a orientação correta para encaixar o componente. Como não tem experiência suficiente para tomar a decisão sozinho, consulta o material fornecido e solicita auxílio ao professor. Enquanto aguarda a orientação, a atividade fica interrompida. Em uma situação diferente, caso o estudante prossiga sem identificar corretamente o procedimento, poderá realizar a instalação de maneira inadequada e precisar desfazer a etapa para corrigir o erro. A dificuldade em compreender o procedimento pode aumentar o tempo necessário para concluir a atividade e prejudicar a confiança do estudante.

## 4.6 Que evidência existe hoje?

| Evidência/fonte | O que sustenta | Limitação |
|---|---|---|
| {{Literatura sobre ensino de hardware e montagem de computadores}} | {{Sustenta a necessidade de conhecimento sobre identificação, função e instalação dos componentes}} | {{Pode abordar métodos tradicionais sem considerar a proposta específica do projeto}} |

|{{Materiais didáticos, tutoriais e vídeos sobre montagem de computadores}}|{{Demonstram como o conteúdo é atualmente apresentado aos estudantes}}|{[Normalmente são materiais passivos, com menor possibilidade de interação e prática}}|

---

# 5. Entendendo o contexto de uso

## 5.1 Onde e em quais situações a interação poderia ocorrer?

{{[F/H/?] ...}}
[H] A interação com o Serious Game poderá ocorrer em diferentes contextos de aprendizagem, como salas de aula, laboratórios de informática, ambientes de estudo e na residência do estudante. Por ser uma aplicação Web, o usuário poderá acessar o sistema por meio de um navegador, permitindo que as atividades sejam realizadas tanto individualmente quanto como atividade complementar orientada por um professor.

[H] Em um contexto educacional, o jogo poderá ser utilizado antes de uma atividade prática com componentes físicos, durante atividades de aprendizagem ou como forma de revisão do conteúdo.

## 5.2 Em quais dispositivos/equipamentos?

{{[F/H/?] ...}}

[F] Os principais dispositivos considerados são smartphones, tablets e computadores/notebooks.

[F] Nos dispositivos móveis, a interação será realizada principalmente por meio de toque na tela. Em computadores e notebooks, a interação poderá utilizar mouse e teclado.

[H] O sistema poderá ser desenvolvido com interface responsiva para adaptar a apresentação do jogo a diferentes tamanhos de tela.


## 5.3 Existem condições físicas relevantes?

Considere iluminação, ruído, mobilidade, conexão, privacidade, uso compartilhado, interrupções, pressão de tempo etc.

{{[F/H/?] ...}}
[F] Por se tratar de uma aplicação Web, o Serious Game poderá ser utilizado em diferentes ambientes, como salas de aula, laboratórios de informática ou na residência do estudante. Não há necessidade de condições físicas específicas de iluminação ou ruído para a utilização da interface.

[F] Uma condição relevante é a disponibilidade de um dispositivo compatível e de conexão com a Internet para acessar a aplicação.

[H] Em dispositivos móveis, o tamanho da tela pode influenciar a interação com os modelos 3D e elementos do jogo, sendo necessário considerar uma interface responsiva e adequada ao uso por toque.

[H] O usuário poderá sofrer interrupções durante a atividade, principalmente quando utilizar o sistema em ambientes externos ou compartilhados. Por isso, o salvamento do progresso poderá permitir que o estudante retome as atividades posteriormente.

## 5.4 Existem fatores sociais ou organizacionais?

Considere papéis, chefias, equipes, permissões, aprovação, responsabilidade profissional, auditoria, turnos e colaboração.

{{[F/H/?] ...}}

[F] O principal contexto social considerado é o educacional, envolvendo estudantes, professores e instituições de ensino ou uso individual.

[H] O professor poderá atuar como orientador da atividade, indicando o uso do Serious Game como complemento às aulas teóricas ou práticas.

[H] A aplicação poderá ser utilizada individualmente ou como parte de uma atividade proposta pelo professor, podendo também permitir atividades em grupo nas quais os estudantes discutam as decisões relacionadas à montagem.

[F] Durante o desenvolvimento e avaliação do projeto, a equipe responsável pelo TCC será responsável pela configuração dos conteúdos, implementação das funcionalidades e realização dos testes.

## 5.5 Existe necessidade de histórico, rastreabilidade ou auditoria?

{{[F/H/?] ...}}
[F] Para o funcionamento básico do Serious Game, não há necessidade de mecanismos formais de auditoria ou rastreabilidade, pois o sistema possui finalidade educacional e não envolve decisões profissionais críticas.

[H] Entretanto, o armazenamento do progresso do estudante, como fases concluídas, pontuação, erros e desempenho, poderá ser utilizado para permitir que o usuário acompanhe sua evolução durante o uso da aplicação.

[H] Durante a avaliação do TCC, dados relacionados ao desempenho dos participantes poderão ser registrados para posterior análise dos resultados, respeitando os procedimentos definidos para a pesquisa.

## 5.6 Um erro pode produzir consequência relevante? Qual?

{{[F/H/?] ...}}

[F] No contexto do Serious Game, um erro cometido pelo estudante durante uma atividade virtual não produz dano físico aos componentes, pois a interação ocorre em um ambiente simulado.

[H] Entretanto, a apresentação de uma informação incorreta, a validação inadequada de uma montagem ou um feedback equivocado pode levar o estudante a compreender ou memorizar um procedimento incorreto.

[H] Caso esse conhecimento seja posteriormente aplicado em uma montagem física, um procedimento inadequado poderá causar mau funcionamento ou, dependendo da ação realizada, danos aos componentes. Por isso, a precisão das informações e das regras de validação do jogo é relevante para a confiabilidade educacional da aplicação.

---

# 6. Entendendo mercado e alternativas existentes

> Nesta entrega faça apenas um **levantamento inicial**. A análise aprofundada ocorre na Entrega 2.
> Um exemplo comercial é o PC Building Simulator, que permite simular montagem e reparo e apresenta instruções passo a passo para iniciantes.


## 6.1 Como pessoas resolvem problemas semelhantes hoje?

| Alternativa atual | Quem usa | Para quê | Status/evidência |
|---|---|---|---|
| {{...}} | {{...}} | {{...}} | {{...}} |

## 6.2 Existem produtos que atuam na mesma área, mesmo sem serem equivalentes ao TCC?

{{[F/H/?] ...}}

## 6.3 Quais interfaces profissionais esse público já conhece?

Exemplos possíveis: ferramentas de banco, IDEs, consoles de nuvem, dashboards, plataformas de dados, ferramentas de monitoramento, painéis de IA, sistemas administrativos.

{{[F/H/?] ...}}

## 6.4 O que essas soluções parecem fazer bem?

{{[F/H/?] ...}}
[F] As soluções existentes parecem apresentar bem os componentes de computador e seus respectivos locais de instalação, utilizando imagens, modelos 3D, vídeos ou simulações.

[F] Simuladores e jogos permitem que o usuário pratique procedimentos de montagem em um ambiente virtual, reduzindo a necessidade de utilizar imediatamente componentes físicos.

[F] Algumas soluções apresentam instruções passo a passo, permitindo que usuários iniciantes acompanhem a sequência necessária para realizar determinadas atividades.

[H] A utilização de elementos de jogo, como desafios, progressão e feedback, pode contribuir para tornar a aprendizagem mais interativa e estimular o usuário a repetir as atividades.

## 6.5 O que parecem fazer mal, dificultar ou não atender?

{{[F/H/?] ...}}
[H] Algumas soluções podem apresentar uma quantidade elevada de informações e funcionalidades, tornando a experiência mais complexa para usuários que estão tendo o primeiro contato com montagem de computadores.

[H] Soluções de simulação mais completas podem exigir computadores com maior capacidade de processamento ou instalação de softwares, dificultando o acesso em dispositivos mais simples.

[H] Algumas alternativas podem estar mais voltadas à simulação de montagem e reparo para usuários interessados em hardware do que especificamente ao processo de aprendizagem introdutória.

[H] Soluções que dependem de equipamentos específicos, como dispositivos de realidade virtual, podem apresentar maior dificuldade de acesso devido à necessidade de hardware adicional.

[?] Ainda é necessário realizar uma análise mais aprofundada das soluções existentes para verificar quais funcionalidades educacionais, recursos de acessibilidade e limitações de uso estão presentes em cada alternativa.

## 6.6 Que padrões de interface ou vocabulário parecem familiares a esse público?

{{[F/H/?] ...}}

[F] O público provavelmente está familiarizado com interfaces baseadas em menus, botões, ícones, imagens e elementos de interação comuns em jogos e aplicações Web.

[F] Termos relacionados a componentes de hardware, como CPU, RAM, GPU, SSD, placa-mãe e fonte de alimentação, são utilizados em materiais e aplicações relacionadas ao tema.

[H] Para usuários iniciantes, termos técnicos podem não ser completamente familiares, sendo necessário apresentar explicações simples e contextualizadas durante o processo de aprendizagem.

[H] Elementos comuns de jogos, como "Iniciar", "Próxima fase", "Pontuação", "Concluir", "Tentar novamente", "Acerto" e "Erro", tendem a ser familiares para usuários que possuem experiência com jogos digitais.

---

# 7. Derivando o escopo de IHC da disciplina

## 7.1 Escolha o caminho do projeto

### Caminho A — TCC já possui interface

Explique qual parte da interface será usada como recorte da disciplina e por que esse fluxo é relevante.

{{O recorte da interface será o fluxo de aprendizagem e montagem virtual de componentes de hardware, desde a seleção de um componente no jogo até sua identificação, visualização das informações, posicionamento no local correto e recebimento de feedback sobre a ação realizada.}}

### Caminho B — TCC não possui interface prevista

Faça o exercício de transferência de uso:

> **Imagine que o TCC foi concluído com sucesso e uma empresa, laboratório ou organização quer transformar a contribuição em algo utilizável. Quem precisaria interagir com ela e para quê?**

Responda:

1. quem poderia contratar/adotar a solução? {{...}}
2. quem seria o usuário direto? {{...}}
3. quem administraria/configuraria? {{...}}
4. quem interpretaria resultados? {{...}}
5. quem tomaria decisões? {{...}}
6. quais dados/entradas seriam necessários? {{...}}
7. quais resultados deveriam ser compreendidos? {{...}}
8. que erros/rupturas seriam possíveis? {{...}}

## 7.2 Qual perfil será priorizado no projeto de IHC?

{{...}}

**Por que esse perfil foi escolhido?** {{...}}

## 7.3 Qual objetivo desse usuário será priorizado?

{{...}}

## 7.4 Que interface será explorada na disciplina?

Complete:

> **Para fins da disciplina de IHC, será projetada uma interface que permita a `{{perfil}}` utilizar `{{capacidade/resultado do TCC}}` para `{{objetivo}}`, no contexto de `{{situação}}`.**

{{...}}

## 7.5 Qual é a relação dessa interface com o TCC?

- [ ] Já fazia parte do TCC.
- [ ] É um aprofundamento de algo parcialmente previsto.
- [ ] É uma extensão conceitual criada para a disciplina.
- [ ] É um protótipo demonstrativo de aplicação potencial.
- [ ] Outra: {{...}}.

> **Declaração:** a interface desenvolvida nesta disciplina é um artefato de aprendizagem de IHC baseado no tema do TCC. Sua inclusão ou implementação no TCC somente ocorrerá se isso for posteriormente decidido pela equipe e pelo orientador.

---

# 8. Levantando possibilidades de interação — sem desenhar ainda

A equipe pode registrar possibilidades para investigação. **Não significa que todas serão implementadas.**

Marque apenas as que parecem plausíveis e explique o objetivo correspondente.

| Possibilidade | Pode fazer sentido? | Objetivo/tarefa que justificaria | Evidência atual |
|---|---|---|---|
| Dashboard/visão geral | sim/não/talvez | {{...}} | {{...}} |
| Configuração/parametrização | sim/não/talvez | {{...}} | {{...}} |
| Entrada/upload/seleção de dados | sim/não/talvez | {{...}} | {{...}} |
| Acompanhamento de processamento | sim/não/talvez | {{...}} | {{...}} |
| Relatório/resultados | sim/não/talvez | {{...}} | {{...}} |
| Histórico com busca/filtros | sim/não/talvez | {{...}} | {{...}} |
| Comparação de resultados | sim/não/talvez | {{...}} | {{...}} |
| Explicabilidade/detalhamento | sim/não/talvez | {{...}} | {{...}} |
| Administração/configurações globais | sim/não/talvez | {{...}} | {{...}} |
| Usuários/perfis/permissões | sim/não/talvez | {{...}} | {{...}} |
| CRUD de entidade do domínio | sim/não/talvez | {{...}} | {{...}} |
| Auditoria/logs | sim/não/talvez | {{...}} | {{...}} |
| Alertas/ocorrências | sim/não/talvez | {{...}} | {{...}} |
| Ajuda/documentação | sim/não/talvez | {{...}} | {{...}} |

> **Atenção:** “login + dashboard + CRUD” não é uma solução universal. Cada padrão deve surgir de uma tarefa real.

---

# 9. Benefícios e ações iniciais

## 9.1 Qual benefício concreto o projeto de IHC pretende oferecer?

| Benefício esperado | Problema/necessidade | Usuário | Status/evidência |
|---|---|---|---|
| {{...}} | {{...}} | {{...}} | {{...}} |

## 9.2 Que ações o usuário deverá conseguir realizar?

| ID | O usuário precisa conseguir... | Para alcançar... | Prioridade inicial |
|---|---|---|---|
| F01 | {{ação}} | {{objetivo}} | alta/média/baixa |

## 9.3 Tecnologias/restrições já definidas no TCC

A tecnologia aparece **agora**, depois do entendimento do uso.

| Tecnologia/restrição | Por que existe | Possível impacto na interação |
|---|---|---|
| {{...}} | {{...}} | {{...}} |

---

# 10. Hipóteses e dúvidas prioritárias

| ID | Hipótese/dúvida | Por que importa | Como poderá ser investigada |
|---|---|---|---|
| H01 | {{...}} | {{...}} | Entrega 2/3/7/... |
| H02 | {{...}} | {{...}} | {{...}} |
| H03 | {{...}} | {{...}} | {{...}} |

Registre em [`../RASTREABILIDADE.md`](../RASTREABILIDADE.md).

---

# 11. Síntese da equipe

| Pergunta | Síntese atual |
|---|---|
| Qual é a contribuição central do TCC? | {{...}} |
| O TCC já previa interface? | {{...}} |
| Quem é o usuário prioritário de IHC? | {{...}} |
| O que ele precisa alcançar? | {{...}} |
| Qual problema/atividade será estudado? | {{...}} |
| Como isso acontece hoje? | {{...}} |
| Qual é o contexto de uso? | {{...}} |
| Que interface/recorte será explorado? | {{...}} |
| Como a interface se relaciona ao TCC? | {{...}} |
| Quais pontos ainda são hipóteses? | {{H01...}} |

### Delimitação

**Dentro do escopo de IHC:** {{...}}  
**Fora do escopo de IHC:** {{...}}  
**Dentro do escopo formal do TCC:** {{...}}  
**Interface da disciplina será implementada no TCC?** não definido / sim / não — {{justificativa, se houver}}

---

# 12. Como esta entrega alimenta as próximas

- **Entrega 2:** verifica mercado, concorrentes e interfaces profissionais representativas.
- **Entrega 3:** detalha perfis e contexto.
- **Entrega 4:** aprofunda situações problemáticas.
- **Entrega 5:** modela tarefas centrais.
- **Entrega 6:** experimenta alternativas em baixa fidelidade.
- **Entrega 7:** investiga hipóteses com dados.
- **Entrega 8:** define restrições e metas de usabilidade.
- **Entregas 9–11:** transformam o recorte em modelo de interação e protótipo.
- **Entregas 12–14:** avaliam a interface construída na disciplina.

A Entrega 1 é uma **fotografia inicial do conhecimento**. Ela pode e deve ser revisada quando surgirem evidências.

---

# 13. Relação com INOVA e comunicação do projeto

Prepare uma explicação de até três frases:

1. **Problema/atividade humana:** {{...}}
2. **Contribuição técnica do TCC:** {{...}}
3. **Como uma pessoa poderia utilizar essa contribuição:** {{...}}

Essa síntese ajuda a apresentar o projeto para público não especializado sem reduzir seu mérito técnico.

---

# Checklist de qualidade

- [x] Está clara a diferença entre tema do TCC, escopo formal do TCC e escopo de IHC.
- [x] A equipe declarou se o TCC já previa interface.
- [ ] Se não previa, foi derivado um usuário plausível e um objetivo de uso.
- [x] A interface de IHC não foi apresentada como obrigação automática do TCC.
- [x] A contribuição do TCC foi descrita sem começar por tecnologias de implementação.
- [x] Usuários diretos e stakeholders foram diferenciados.
- [x] Foram considerados profissionais que configuram, administram, interpretam ou decidem, quando pertinente.
- [x] Objetivo do usuário não foi confundido com objetivo do projeto.
- [x] Processo/problema atual foi descrito antes da solução.
- [ ] Existe situação concreta de uso/problema.
- [ ] Contexto físico, social/organizacional, dispositivos e consequências de erro foram considerados.
- [ ] Mercado/alternativas existentes foram levantados inicialmente.
- [ ] Possibilidades como dashboard, relatório, histórico, filtros e CRUD foram tratadas como hipóteses de solução, não como requisitos automáticos.
- [ ] Cada possibilidade de interface tem um objetivo/tarefa que poderia justificá-la.
- [ ] Afirmações relevantes estão marcadas `[F]`, `[H]` ou `[?]`.
- [ ] Hipóteses prioritárias receberam IDs e foram para a rastreabilidade.
- [ ] O recorte de IHC é viável para modelar, prototipar e avaliar no semestre.
- [ ] A equipe consegue explicar problema humano → contribuição computacional → forma de uso.
