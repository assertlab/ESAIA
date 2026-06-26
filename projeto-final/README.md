# 🎼 Guia do Projeto Final — ESAIA 2026.1

<div align="center">

![Disciplina](https://img.shields.io/badge/Disciplina-IF1015%20ESAIA-blue)
![Semestre](https://img.shields.io/badge/Semestre-2026.1-orange)
![Metodologia](https://img.shields.io/badge/Metodologia-Sinfonia-purple)
![Peso](https://img.shields.io/badge/Peso%20na%20nota-75%25-red)

**Projeto final estruturado pela Metodologia Sinfonia**

[⬅️ Voltar ao README da disciplina](../README.md) · [📅 Planejamento](../PLANEJAMENTO_2026_1.md)

</div>

---

## 📋 Índice

- [Visão Geral](#-visão-geral)
- [Objetivos](#-objetivos)
- [Formação de Equipes](#-formação-de-equipes)
- [A Jornada pela Sinfonia](#-a-jornada-pela-sinfonia)
- [Os 14 Artefatos](#-os-14-artefatos)
- [Entregáveis por Checkpoint](#-entregáveis-por-checkpoint)
- [Avaliação e Critérios](#-avaliação-e-critérios)
- [Relatório Final](#-relatório-final)
- [Templates](#-templates)
- [Submissão](#-submissão)
- [Integridade Acadêmica](#-integridade-acadêmica)
- [Dicas de Sucesso](#-dicas-de-sucesso)

---

## 🎯 Visão Geral

O projeto final é o componente central da disciplina (**75% da nota**) e consiste no desenvolvimento, em equipe, de uma **solução de software intensiva em IA** que resolva um problema real em alguma subdisciplina da Engenharia de Software (requisitos, design, codificação, testes, DevOps, manutenção, evolução — alinhado ao SWEBOK).

O projeto é conduzido ao longo das **Aulas 16 a 36**, estruturado pelos **4 Movimentos da Metodologia Sinfonia** e validado em **4 checkpoints** avaliativos.

O projeto produz **duas entregas indissociáveis** — uma sem a outra está incompleta:

- 🛠️ **A Aplicação** — a ferramenta funcional assistida por IA (o produto, que evidencia o *resultado*).
- 📓 **O Workflow Document** — o diário de bordo do desenvolvimento assistido por IA (o processo, que evidencia o *aprendizado*). É um documento vivo, atualizado a cada fase, e inclui a análise de **economicidade** do projeto (consumo de tokens, esforço humano real e o contrafactual de um desenvolvimento equivalente feito por humanos).

> **Referência da metodologia:** Garcia, V. C., & Medeiros, R. P. (2025). *Sinfonia: Orquestrando a Inteligência Artificial*. ASSERT Lab. [github.com/assertlab/sinfonia](https://github.com/assertlab/sinfonia)

---

## 🏆 Objetivos

Ao concluir o projeto final, a equipe deverá ser capaz de:

1. **Aplicar** a Metodologia Sinfonia de ponta a ponta, produzindo os 14 artefatos que a estruturam.
2. **Integrar** LLMs e técnicas de IA generativa em uma solução funcional de engenharia de software.
3. **Projetar e documentar** prompts de forma rigorosa, versionada e avaliável (Catálogo de Registros de Prompt).
4. **Desenhar** a arquitetura da solução com o C4 Model, justificando decisões e trade-offs.
5. **Planejar e executar** um experimento para validar hipóteses sobre a solução.
6. **Avaliar criticamente** a qualidade, segurança e confiabilidade dos outputs da IA (alucinações, vieses, vulnerabilidades).
7. **Medir e aprender** com feedback real de usuários, tomando uma decisão estratégica fundamentada.
8. **Documentar e analisar a economicidade** do desenvolvimento assistido por IA, comparando o custo real ao contrafactual de um desenvolvimento humano equivalente.
9. **Comunicar** o trabalho de forma profissional — em código, documentação, relatório e apresentação.

---

## 👥 Formação de Equipes

- Equipes de **3 a 4 alunos**.
- Formadas na **Aula 16** (kick-off do projeto).
- Cada equipe define um(a) **líder** responsável pela coordenação e pela interlocução com o professor.
- Cada equipe trabalha em um **repositório GitHub próprio**, dentro da organização da disciplina.

---

## 🎼 A Jornada pela Sinfonia

| Movimento | Aulas | Propósito | Checkpoint |
|-----------|-------|-----------|------------|
| 🎯 **Exposição** | 16–21 | Alinhar estratégia e definir o problema | **CP1** (Aula 21) |
| 🎨 **Composição** | 22–26 | Desenhar a solução técnica | **CP2** (Aula 26) |
| 🔨 **Ensaio** | 27–32 | Construir, testar e preparar lançamento | **CP3** (Aula 32) |
| 📊 **Ressonância** | 33–36 | Medir, aprender e apresentar | **Apresentação Final** (Aulas 35–36) |

---

## 📦 Os 14 Artefatos

A Sinfonia define 14 artefatos concretos que guiam o projeto. Todos devem estar versionados no repositório.

### 🎯 Exposição (6)
1. **Canvas de Estratégia e Ação do Projeto** — problema, contexto de negócio, objetivos.
2. **Personas** (Persona Model Canvas) — usuários-alvo e mapa de empatia.
3. **Declaração de Missão e Visão** — propósito e estado futuro desejado.
4. **Métricas de Sucesso** — KPIs técnicos e de negócio.
5. **Matriz de Priorização** (Impacto × Esforço) — escolha da solução.
6. **Escopo do MVP** — features e não-features.

### 🎨 Composição (4)
7. **C4 Model** — arquitetura (Contexto, Contêiner, Componente).
8. **Catálogo de Registros de Prompt** — prompts versionados e avaliados.
9. **Canvas de Design de Experimento** — hipótese, métricas, critérios de decisão.
10. **Registro de Decisões Arquiteturais** — escolhas-chave, trade-offs, riscos.

### 🔨 Ensaio (2)
11. **Canvas de Testes e Validação** — testes funcionais, de qualidade de IA e edge cases.
12. **Checklist de Lançamento** — prontidão técnica, segurança, conformidade, documentação.

### 📊 Ressonância (2)
13. **Painel de Feedback e Insights** — análise quantitativa e qualitativa do feedback.
14. **Canvas de Escalabilidade** — caminhos de evolução além do MVP.

> 📓 **Além dos 14 artefatos:** o **Workflow Document** (diário de bordo do desenvolvimento assistido por IA, com a análise de economicidade) é mantido em paralelo desde o início do projeto e atualizado a cada fase. Ele é o segundo entregável indissociável e entra como anexo obrigatório do Relatório Final.

---

## ✅ Entregáveis por Checkpoint

### Checkpoint 1 — Exposição (Aula 21) · Apresentação 10 min · **10%**
- Canvas de Estratégia e Ação do Projeto
- Personas (2–3) com mapa de empatia
- Declaração de Missão/Visão e Métricas de Sucesso
- Matriz de Priorização e Escopo do MVP
- Documento consolidado (5–8 páginas)

### Checkpoint 2 — Composição (Aula 26) · Apresentação + demo 10 min · **15%**
- C4 Model (Níveis 1–2 obrigatórios; 3 recomendado)
- Catálogo de Registros de Prompt v1.0 (mínimo 5–7 prompts)
- Canvas de Design de Experimento
- Registro de Decisões Arquiteturais
- Demonstração funcional de prompts-chave

### Checkpoint 3 — Ensaio (Aula 32) · Demo ao vivo 12 min · **10%**
- MVP funcional e demonstrável
- Canvas de Testes e Validação
- Relatório de segurança (vulnerabilidades + mitigação)
- Checklist de Lançamento
- Repositório com código, testes automatizados e CI/CD em execução
- Workflow Document atualizado (uso de IA + economicidade das fases anteriores)

### Apresentação Final — Ressonância (Aulas 35–36) · 18 min + 7 min Q&A
- Painel de Feedback e Insights
- Análise de métricas e validação de hipóteses
- Decisão estratégica documentada
- Canvas de Escalabilidade
- **Relatório Final** (PDF, com seção de economicidade) + **Workflow Document completo** (anexo) + **sistema funcional** + **repositório completo**

---

## 📊 Avaliação e Critérios

### Pesos do projeto final (75%)

| Componente | Aula | Peso |
|------------|------|------|
| Checkpoint 1 — Exposição | 21 | 10% |
| Checkpoint 2 — Composição | 26 | 15% |
| Checkpoint 3 — Ensaio | 32 | 10% |
| Entrega Final (sistema + relatório + artefatos) | 35–36 | 37% |
| Contribuição Individual (peer review + commits) | — | 3% |

> ⚠️ **Nota:** há uma divergência de pesos entre as versões do Plano de Ensino (que separa "Entrega Final 30%" + "Apresentação 7%") e o README/Project Instructions (que consolida "Entrega Final 37%"). **Esta tabela segue a versão consolidada do repositório (37%); confirmar a versão oficial para 2026.1 antes do fechamento das notas.**

### Critérios da entrega final

| Critério | Peso |
|----------|------|
| 🚀 Inovação e criatividade | 20% |
| ⚙️ Funcionalidade e aplicação prática | 25% |
| 💎 Qualidade técnica (código, arquitetura, testes) | 20% |
| 📚 Documentação profissional | 15% |
| 🧐 Análise crítica (limitações, ética, vieses) | 10% |
| 🎤 Apresentação e comunicação | 10% |

A avaliação de cada checkpoint usa uma **rubrica de 4 níveis** — *Insuficiente · Em desenvolvimento · Proficiente · Exemplar* — disponível em [`../rubricas/`](../rubricas/).

---

## 📄 Relatório Final

O **Relatório Final** é artefato obrigatório de avaliação e deve documentar a jornada completa pelos 4 Movimentos. Ele é avaliado **em conjunto** com o repositório, os artefatos e o sistema funcional.

Inclui uma seção dedicada à **economicidade do desenvolvimento assistido por IA** (consolidado das três camadas: custo real de IA, esforço humano real e contrafactual humano) e traz o **Workflow Document completo como anexo obrigatório**.

- **Template:** [`./Template_Relatorio_Final_Projeto.md`](./Template_Relatorio_Final_Projeto.md)
- **Formato:** PDF versionado no repositório.
- **Entrega:** no repositório **e** por e-mail ao professor ao final da apresentação.

---

## 📋 Templates

Os templates dos 14 artefatos e do relatório ficam disponíveis na pasta [`./templates/`](./templates/):

| Artefato | Movimento | Template |
|----------|-----------|----------|
| Canvas de Estratégia e Ação | Exposição | `templates/01-canvas-estrategia.md` |
| Persona Model Canvas | Exposição | `templates/02-personas.md` |
| Declaração de Missão/Visão | Exposição | `templates/03-missao-visao.md` |
| Métricas de Sucesso | Exposição | `templates/04-metricas.md` |
| Matriz de Priorização | Exposição | `templates/05-matriz-priorizacao.md` |
| Escopo do MVP | Exposição | `templates/06-escopo-mvp.md` |
| C4 Model | Composição | `templates/07-c4-model.md` |
| Catálogo de Registros de Prompt | Composição | `templates/08-catalogo-prompts.md` |
| Canvas de Design de Experimento | Composição | `templates/09-canvas-experimento.md` |
| Registro de Decisões Arquiteturais | Composição | `templates/10-decisoes-arquiteturais.md` |
| Canvas de Testes e Validação | Ensaio | `templates/11-canvas-testes.md` |
| Checklist de Lançamento | Ensaio | `templates/12-checklist-lancamento.md` |
| Painel de Feedback e Insights | Ressonância | `templates/13-painel-feedback.md` |
| Canvas de Escalabilidade | Ressonância | `templates/14-canvas-escalabilidade.md` |
| **Workflow Document** (uso de IA + economicidade) | — | `templates/workflow-document.md` |
| **Relatório Final** | — | [`Template_Relatorio_Final_Projeto.md`](./Template_Relatorio_Final_Projeto.md) |

> 💡 Os templates dos 14 artefatos ainda estão em produção. Conforme forem publicados, os links acima passam a apontar para os arquivos correspondentes.

---

## 📤 Submissão

- **Código:** repositório GitHub da equipe (com `README.md`, `BUILD.md`, diagramas e os 14 artefatos).
- **Documentos:** Google Classroom + repositório.
- **Relatório Final:** PDF no repositório **e** por e-mail ao professor.
- **Deadline:** 23:59 da data especificada para cada entrega.
- **Penalidade por atraso:** −10% por dia (máximo 3 dias).
- **Extensões:** solicitação formal com antecedência mínima de 48h e justificativa adequada.

---

## ⚖️ Integridade Acadêmica

- O uso de ferramentas de IA é **permitido e incentivado**, mas deve ser **documentado e atribuído** conforme o [Código de Conduta para Uso Ético de IA](../docs/Codigo_de_Conduta.md).
- Todo código e texto gerado por IA deve ser **compreendido e validado** pela equipe.
- Plágio ou uso não atribuído de qualquer fonte (humana ou IA) resulta em **nota zero** e possíveis sanções disciplinares.
- A **Contribuição Individual** é avaliada por peer review e histórico de commits — contribua de forma consistente e rastreável.

---

## 💡 Dicas de Sucesso

✅ **Comece cedo e use os checkpoints** — eles existem para validar o rumo antes que seja tarde para corrigir.

✅ **Versione tudo** — os 14 artefatos no repositório, prompts no catálogo, decisões arquiteturais registradas.

✅ **Documente o uso de IA de forma transparente** — é critério de avaliação e princípio da disciplina.

✅ **Mantenha o Workflow Document vivo** — registre o uso de IA e os dados de economicidade (tokens, horas) ao final de *cada* fase. Reconstruir esses números no fim do semestre é inviável.

✅ **Teste a qualidade dos outputs da IA**, não só a funcionalidade — alucinação e segurança são centrais na ESAIA.

✅ **Ensaie a apresentação final** — timing é crítico (18 min) e a demo ao vivo deve estar à prova de falhas (tenha um plano B).

✅ **Distribua o trabalho de forma equilibrada** — commits e peer review refletem a contribuição individual.

---

<div align="center">

**Boa jornada pela Sinfonia! 🎼**

[⬅️ Voltar ao README da disciplina](../README.md)

*Prof. Vinicius Cardoso Garcia · CIn/UFPE · IF1015 ESAIA 2026.1*

</div>
