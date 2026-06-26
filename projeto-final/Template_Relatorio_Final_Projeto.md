# ESAIA — Engenharia de Software Assistida por IA (IF1015)
# Relatório Final do Projeto — 2026.1

> **Template oficial.** Substitua todos os campos entre `< >` pelo conteúdo da sua equipe. Mantenha a estrutura dos 4 Movimentos da Sinfonia. Itens marcados como *(opcional)* podem ser omitidos se não se aplicarem ao seu projeto — mas justifique a omissão quando relevante.

---

## Capa

- **Disciplina:** IF1015 — Engenharia de Software Assistida por IA (ESAIA)
- **Semestre:** 2026.1
- **Professor:** Vinicius Cardoso Garcia (vcg@cin.ufpe.br)
- **Título do projeto:** `<Nome do Projeto>`
- **Nome da equipe:** `<Nome da Equipe>`
- **Integrantes** (destaque o(a) líder com **negrito**):
  - **`<Nome — login@cin>`** *(líder)*
  - `<Nome — login@cin>`
  - `<Nome — login@cin>`
  - `<Nome — login@cin>`
- **Repositório Git:** `<URL — deve conter README.md, BUILD.md, diagramas, os 14 artefatos e o Workflow Document>`
- **Sistema em produção** *(se aplicável):* `<URL>`
- **Data de entrega:** `<DD/MM/2026>`

Recife, `<Data da entrega>`

---

## Sumário

1. Introdução
2. Metodologia
3. Movimento 1 — Exposição (Alinhar Estratégia)
4. Movimento 2 — Composição (Desenhar a Solução)
5. Movimento 3 — Ensaio (Construir e Testar)
6. Movimento 4 — Ressonância (Medir e Aprender)
7. Economicidade do Desenvolvimento Assistido por IA
8. Discussões Técnicas e Estratégicas
9. Considerações Éticas
10. Lições Aprendidas e Reflexões Finais
11. Referências
12. Apêndices

---

## 1. Introdução

- **Contextualização do problema de engenharia de software** que o projeto aborda — qual subdisciplina do SDLC/SWEBOK é o foco (requisitos, design, codificação, testes, DevOps, manutenção, etc.).
- **Objetivo geral e objetivos específicos** da solução.
- **Justificativa do uso de IA generativa e LLMs:** por que a IA é a abordagem adequada para este problema, e o que ela agrega em relação a uma solução tradicional.
- **Visão geral da abordagem** com a Metodologia Sinfonia (panorama dos 4 movimentos percorridos).

---

## 2. Metodologia

- **As duas entregas indissociáveis:** este projeto produz dois artefatos complementares — a **Aplicação** (o produto, que evidencia o resultado) e o **Workflow Document** (o diário de bordo do desenvolvimento assistido por IA, que evidencia o aprendizado). Uma sem a outra está incompleta. Resuma aqui como ambas foram conduzidas em paralelo.
- **Aplicação da Metodologia Sinfonia** ao projeto: como os 4 movimentos estruturaram o trabalho.
- **Gestão do trabalho em equipe:** organização em sprints, divisão de responsabilidades, ferramentas de apoio (board de tarefas, Discord, etc.).
- **Workflow Document como documento vivo:** registre que o diário de bordo foi mantido e atualizado a cada fase, capturando tanto o uso qualitativo de IA quanto os dados de economicidade (consumo de tokens, esforço humano e contrafactual). O documento completo entra como anexo obrigatório (ver Seção 12) e seu consolidado é analisado na Seção 7.
- **Etapas e marcos principais** da execução, mapeados aos checkpoints da disciplina (CP1–Exposição, CP2–Composição, CP3–Ensaio, Apresentação Final–Ressonância).

---

## 3. Movimento 1 — Exposição (Alinhar Estratégia)

> Artefatos da Exposição: Canvas de Estratégia e Ação, Personas, Declaração de Missão/Visão, Métricas de Sucesso, Matriz de Priorização (Impacto × Esforço), Escopo do MVP.

- **Canvas de Estratégia e Ação do Projeto** (resumo): problema, contexto de negócio e objetivos de alto nível.
- **Personas principais** (Persona Model Canvas) com justificativa e mapa de empatia.
- **Declaração de Missão e Visão** e seu alinhamento com princípios éticos.
- **Métricas de sucesso** definidas (mix de métricas técnicas e de negócio).
- **Matriz de Impacto × Esforço** e decisão de priorização.
- **Escopo do MVP:** features e *não-features* (o que ficou explicitamente de fora).

---

## 4. Movimento 2 — Composição (Desenhar a Solução)

> Artefatos da Composição: C4 Model, Catálogo de Registros de Prompt, Canvas de Design de Experimento, Registro de Decisões Arquiteturais.

- **Arquitetura com C4 Model** (Níveis 1–Contexto e 2–Contêiner obrigatórios; Nível 3–Componente recomendado). Indicar **onde a IA/LLM se integra** na arquitetura.
- **Registro de Decisões Arquiteturais:** escolhas-chave, trade-offs considerados e riscos identificados.
- **Catálogo de Registros de Prompt:** os prompts centrais da solução, cada um com objetivo, template, parâmetros, exemplos de input/output e critérios de avaliação. Inclua **versionamento** e, quando houver, comparação A/B entre variações.
- **Canvas de Design de Experimento:** hipótese a validar, métricas, condições de teste, riscos e critérios de decisão (pivotar / perseverar / parar).
- **Protótipos, wireframes ou mockups** iniciais *(se aplicável)*.

---

## 5. Movimento 3 — Ensaio (Construir e Testar)

> Artefatos do Ensaio: Canvas de Testes e Validação, Checklist de Lançamento.

- **Estratégia de desenvolvimento e tecnologias** adotadas; organização das sprints.
- **Fluxo de integração com LLMs** (APIs, pipelines, salvaguardas).
- **Canvas de Testes e Validação:** testes funcionais, testes de qualidade de outputs do LLM, edge cases, performance/latência. Incluir avaliação de **alucinação** e estratégias de mitigação.
- **Evidências de versionamento:** commits, branches, pull requests, CI/CD em execução.
- **Análise de segurança** (Aula 30): vulnerabilidades identificadas (prompt injection, data leakage, etc.), severidade e plano de mitigação.
- **Checklist de Lançamento** preenchido e validado.
- **Evidências de funcionamento:** screenshots, prints ou vídeo da aplicação; link para o sistema hospedado *(se aplicável)*.

---

## 6. Movimento 4 — Ressonância (Medir e Aprender)

> Artefatos da Ressonância: Painel de Feedback e Insights, Canvas de Escalabilidade.

- **Lançamento e coleta de feedback:** método (soft launch, beta, usuários simulados seguindo as personas), quantidade de participantes e instrumentos usados.
- **Painel de Feedback e Insights:** análise quantitativa (cálculo das métricas do Canvas de Experimento) e qualitativa (temas recorrentes, observações).
- **Validação das hipóteses:** o que foi confirmado ou refutado.
- **Decisão estratégica** documentada e justificada (otimizar / pivotar / perseverar / parar).
- **Canvas de Escalabilidade:** caminhos para evolução da solução além do MVP.

---

## 7. Economicidade do Desenvolvimento Assistido por IA

> Esta seção apresenta o **consolidado** das três camadas de economicidade registradas no Workflow Document ao longo do projeto. O documento completo, com os dados por fase, entra como anexo obrigatório (Seção 12). O objetivo é responder: *qual foi o custo real do desenvolvimento assistido por IA, comparado a uma estimativa do custo de um desenvolvimento equivalente feito integralmente por humanos?*

### 7.1 Camada 1 — Custo real de IA (total do projeto)

| Fase | Tokens entrada | Tokens saída | Custo IA (USD) | Custo IA (R$) |
|------|---------------|-------------|---------------|--------------|
| Exposição | | | | |
| Composição | | | | |
| Ensaio | | | | |
| Ressonância | | | | |
| **Total** | | | | |

> Conversão USD → BRL: indicar a cotação e a data de fechamento usada.

### 7.2 Camada 2 — Esforço humano real (consolidado)

> Síntese das horas humanas efetivamente gastas com assistência de IA, por fase. Detalhamento por atividade e membro fica no Workflow Document anexo.

| Fase | Horas humanas com IA | Observações |
|------|---------------------|-------------|
| Exposição | | |
| Composição | | |
| Ensaio | | |
| Ressonância | | |
| **Total** | | |

### 7.3 Camada 3 — Custo contrafactual humano (total do projeto)

| Fase | Horas totais estimadas (sem IA) | Custo humano estimado (R$) |
|------|--------------------------------|---------------------------|
| Exposição | | |
| Composição | | |
| Ensaio | | |
| Ressonância | | |
| **Total** | | |

> Perfis de referência (Júnior / Pleno / Sênior / Arquiteto) e faixas salariais devem ser os mesmos documentados no Workflow Document, com a fonte indicada.

### 7.4 Análise comparativa

- **Custo total com IA (R$):** `<custo de IA convertido + horas de supervisão/revisão humana>`
- **Custo total estimado sem IA (R$):** `<custo contrafactual>`
- **Razão de economicidade:** `<custo sem IA / custo com IA>`
- **Saving estimado (R$):** `<diferença absoluta>`
- **Saving estimado (%):** `<diferença percentual>`

### 7.5 Limitações da análise

Discuta criticamente o que os números *realmente* indicam. Considere ao menos: (1) o contrafactual é uma estimativa subjetiva, sujeita a viés de retrospecto; (2) o custo com IA não inclui a curva de aprendizado das ferramentas; (3) custo menor não implica qualidade equivalente; (4) atividades em que a IA *aumentou* o tempo total (retrabalho, revisão de outputs incorretos) devem ser registradas explicitamente. Esta reflexão crítica é parte avaliada do relatório — não basta apresentar os números.

---

## 8. Discussões Técnicas e Estratégicas

- Decisões arquiteturais justificadas e avaliação de alternativas técnicas.
- Integrações realizadas (APIs, bases de dados, ferramentas externas, LLMs).
- Desafios técnicos enfrentados e como foram superados.
- Trade-offs entre qualidade, custo (tokens/latência) e complexidade.

---

## 9. Considerações Éticas

- Identificação de riscos, vieses e impacto social da solução.
- Estratégias de mitigação adotadas.
- Transparência e explicabilidade do uso de IA.
- **Atribuição do uso de IA** no desenvolvimento, conforme o Código de Conduta da disciplina.

---

## 10. Lições Aprendidas e Reflexões Finais

- Reflexões sobre a experiência com a Metodologia Sinfonia (qual movimento foi mais desafiador? qual mais valioso?).
- Avaliação da proposta de valor entregue.
- Pontos de melhoria para a solução e sugestões para a metodologia.
- Aprendizados sobre o uso de IA generativa na prática.
- **Relato individual:** cada integrante escreve um parágrafo sobre sua contribuição e aprendizado.

---

## 11. Referências

- Fontes teóricas, técnicas e científicas utilizadas (artigos, papers, repositórios, APIs).
- Leituras de apoio da disciplina (Sinfonia, C4 Model, SWEBOK, e demais referências do Plano de Ensino).

---

## 12. Apêndices

- **Workflow Document completo** *(obrigatório):* o diário de bordo do desenvolvimento assistido por IA, com as três camadas de economicidade detalhadas por fase, atividade e membro. É o segundo entregável indissociável do projeto (ver Seção 2) e a base do consolidado da Seção 7.
- Artefatos completos (os 14 canvases na íntegra).
- Catálogo de Prompts completo.
- Prints, logs de commits, quadro de tarefas e evidências complementares.

---

*Relatório elaborado para a disciplina IF1015 — ESAIA, CIn/UFPE, 2026.1. Metodologia Sinfonia (Garcia & Medeiros, 2025).*
