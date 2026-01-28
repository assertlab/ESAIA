# 🎓 Engenharia de Software Assistida por IA (ESAIA)

<div align="center">

![UFPE](https://img.shields.io/badge/UFPE-Centro%20de%20Inform%C3%A1tica-blue)
![Curso](https://img.shields.io/badge/Curso-Sistemas%20de%20Informa%C3%A7%C3%A3o-green)
![Semestre](https://img.shields.io/badge/Semestre-2026.1-orange)
![Licença](https://img.shields.io/badge/Licen%C3%A7a-CC%20BY--NC--SA%204.0-lightgrey)

**Repositório oficial da disciplina IF1015 - Tópicos Avançados em Sistemas de Informação 6**

[Centro de Informática](http://www.cin.ufpe.br) | [UFPE](http://www.ufpe.br)

</div>

---

## 📋 Índice

- [Sobre a Disciplina](#sobre-a-disciplina)
- [Informações Gerais](#informações-gerais)
- [Metodologia Sinfonia](#metodologia-sinfonia)
- [Pré-requisitos](#pré-requisitos)
- [Proposta de Valor](#proposta-de-valor)
- [Objetivos](#objetivos)
- [Competências Esperadas](#competências-esperadas)
- [Estrutura da Disciplina](#estrutura-da-disciplina)
- [Avaliação](#avaliação)
- [Estrutura do Repositório](#estrutura-do-repositório)
- [Como Usar Este Repositório](#como-usar-este-repositório)
- [Recursos Didáticos](#recursos-didáticos)
- [Contato](#contato)
- [Referências](#referências)

---

## 📚 Sobre a Disciplina

Esta disciplina de tópicos avançados explora a aplicação da **Inteligência Artificial (IA)**, com ênfase em **Modelos de Linguagem de Grande Escala (LLMs)**, para aprimorar o ciclo de vida do desenvolvimento de software (SDLC). 

### 🎯 Destaques

- 🤖 **Foco em LLMs**: Aprenda a utilizar GPT-X, Claude, Gemini e outras ferramentas de IA
- 🛠️ **Hands-on**: Mini-projetos práticos + projeto final substancial
- 🎼 **Metodologia Sinfonia**: Framework estruturado testado em 4 semestres no CIn/UFPE
- 🔒 **Ética e Segurança**: Abordagem crítica sobre hallucinations, vieses e vulnerabilidades
- 💼 **Portfolio**: Projetos públicos para demonstrar suas habilidades
- 🎤 **Networking**: Palestras com profissionais da indústria e pesquisadores

A disciplina aborda como a IA pode atuar como ferramenta indispensável para criação e gerenciamento de sistemas de software complexos, impactando **confiabilidade**, **desempenho**, **resiliência**, **segurança** e **qualidade do código gerado**.

Também exploramos limitações atuais dos LLMs, incluindo **alucinações**, **vieses** e questões de **propriedade intelectual**.

### 🚀 Jornada de Aprendizagem

Por meio de **mini-projetos práticos incrementais** e um **projeto final em equipe**, os alunos percorrerão uma jornada de Design, Projeto e Construção de soluções assistidas por IA para otimizar e inovar em subdisciplinas da engenharia de software, alinhando-se com o escopo do **SWEBOK** (Software Engineering Body of Knowledge).

---

## ℹ️ Informações Gerais

### 👨‍🏫 Instrutor

- **Professor:** Vinicius Cardoso Garcia
- **E-mail:** [vcg@cin.ufpe.br](mailto:vcg@cin.ufpe.br)
- **Website:** [viniciusgarcia.me](https://viniciusgarcia.me)

### 📍 Local e Horário

- **Centro de Informática - UFPE**
- **Horários:** 
  - Segunda-feira: 17:00-18:40
  - Terça-feira: 18:50-20:30
- **Sala:** E-112, Bloco E
- **Aulas práticas:** Lab G2 (preferencialmente)

### 📅 Período

- **Semestre:** 2026.1
- **Carga Horária:** 60 horas (30 aulas de 2 horas)
- **Créditos:** 4

### 🔗 Links Importantes

- **Planejamento 2026.1:** [📅 Cronograma Detalhado de Aulas](./PLANEJAMENTO.md)
- **Plano de Ensino:** [📄 Plano Completo](./docs/Plano_de_Ensino.md)
- **Código de Conduta:** [⚖️ Uso Ético de IA](./docs/Codigo_de_Conduta.md)
- **Canal Discord:** [💬 Comunidade da Disciplina](#) *(em breve)*
- **GitHub Organization:** [🐙 ESAIA-2026-1](#) *(em breve)*

### 📋 Código da Disciplina

- **Graduação:** [IF1015] - Tópicos Avançados em Sistemas de Informação X
- **Nome Fantasia:** Engenharia de Software Assistida por IA (ESAIA)

---

## 🎼 Metodologia Sinfonia

Um dos diferenciais desta disciplina é o uso da **[Metodologia Sinfonia](https://github.com/assertlab/sinfonia)** para estruturar o projeto final. A Sinfonia é um framework ágil para design e evolução de produtos intensivos em IA, desenvolvida pelos professores Vinicius Cardoso Garcia e Rodrigo Pessoa Medeiros, testada e refinada ao longo de 4 semestres no CIn/UFPE.

### Os 4 Movimentos da Sinfonia

<div align="center">

```
┌────────────────────────────────────────────────────────────┐
│                       METODOLOGIA SINFONIA                       │
├────────────────────────────────────────────────────────────┤
│                                                                  │
│  🎯 Movimento 1: EXPOSIÇÃO (Aulas 16-21)                         │
│     → Alinhar estratégia e definir problema                      │
│     → Canvas de Estratégia, Personas, Missão/Visão               │
│                                                                  │
│  🎨 Movimento 2: COMPOSIÇÃO (Aulas 22-26)                        │
│     → Desenhar a solução técnica                                 │
│     → C4 Model, Catálogo de Prompts, Design de Experimento       │
│                                                                  │
│  🔨 Movimento 3: ENSAIO (Aulas 27-32)                            │
│     → Construir, testar e preparar lançamento                    │
│     → MVP, Canvas de Testes, Checklist de Lançamento             │
│                                                                  │
│  📊 Movimento 4: RESSONÂNCIA (Aulas 33-36)                       │
│     → Medir, aprender e decidir próximos passos                  │
│     → Painel de Feedback, Análise de Métricas, Decisões          │
│                                                                  │
└────────────────────────────────────────────────────────────┘
```

</div>

### 📋 Artefatos da Sinfonia

A metodologia define **14 artefatos concretos** que guiam o desenvolvimento do projeto:

**Exposição (6):** Canvas de Estratégia, Personas, Missão/Visão, Métricas, Matriz de Priorização, Escopo MVP

**Composição (4):** C4 Model, Catálogo de Prompts, Canvas de Experimento, Decisões Arquiteturais

**Ensaio (2):** Canvas de Testes, Checklist de Lançamento

**Ressonância (2):** Painel de Feedback, Canvas de Escalabilidade

> 💡 **Saiba mais:** Garcia, V. C., & Medeiros, R. P. (2025). *Sinfonia: Orquestrando a Inteligência Artificial*. ASSERT Lab. [GitHub com o Playboook da Metodologia Sinfonia](https://github.com/assertlab/sinfonia)

---

## 📋 Pré-requisitos

### ✅ Obrigatórios

- **IF977** - Engenharia de Software e Sistemas (ou equivalente)
- **Fundamentos de Programação** (IF669 ou equivalente)
- **Experiência comprovada com Desenvolvimento de Software** (projetos em disciplinas anteriores)
- **Familiaridade com Git/GitHub** (versionamento de código)

### 🎯 Altamente Recomendados

- **IFXXX** - Sistemas Inteligentes (ou equivalente em IA)
- **IFXXX** - Aprendizado de Máquina
- **IFXXX** - Gerência de Projetos de Software
- Experiência prévia com APIs REST
- Conhecimento básico de Docker/Podman e containerização
- Familiaridade com IDEs (VSCode, VSCodiuem, JetBrains, PyCharm, etc.)

### 💡 Conhecimentos Desejáveis

- Processamento de Linguagem Natural (NLP)
- Testes automatizados (Unit Testing, Integration Testing)
- CI/CD (Continuous Integration/Continuous Deployment)
- Cloud Computing (AWS, Azure, ou GCP)
- Metodologias Ágeis (Scrum, Kanban)

> ⚠️ **Nota:** Alunos sem todos os pré-requisitos recomendados deverão dedicar tempo adicional ao nivelamento na **Aula 0** (pré-semestre).

---

## 💎 Proposta de Valor

### Para o Aluno

🎯 **Preparação para o Mercado de Trabalho do Futuro**
- Habilidades em alta demanda no mercado atual
- Experiência com ferramentas de IA de ponta (GitHub Copilot, Claude Code, GPT-*, etc.)
- Portfolio profissional com projetos reais

🧠 **Habilidades Técnicas e Analíticas**
- Implementação e gerenciamento de ferramentas de IA
- Avaliação crítica de resultados: qualidade, confiabilidade, ética
- Prompt Engineering para Engenharia de Software

🛡️ **Consciência Ética e Social**
- Compreensão de vieses, privacidade e propriedade intelectual
- Abordagem responsável na aplicação de IA
- Análise de hallucinations e limitações de LLMs

🚀 **Inovação e Criatividade**
- Desenvolvimento de soluções únicas usando IA
- Exploração de novas fronteiras tecnológicas
- Pensamento crítico e resolução de problemas complexos

🤝 **Colaboração e Networking**
- Trabalho em equipe em projetos práticos
- Palestras com profissionais da indústria
- Interação com pesquisadores de ponta

### Para a Carreira

- ✅ Experiência prática com ferramentas usadas pela indústria
- ✅ Desenvolvimento de soft skills (comunicação, apresentações, teamwork)
- ✅ Compreensão profunda das tendências futuras em ES
- ✅ Diferencial competitivo no mercado de trabalho
- ✅ Networking valioso com profissionais e acadêmicos

---

## 🎯 Objetivos

### Objetivo Geral

Capacitar os alunos a **compreender**, **aplicar** e **avaliar criticamente** ferramentas e técnicas de Inteligência Artificial, especialmente LLMs, em diferentes fases do ciclo de vida de desenvolvimento de software, desenvolvendo soluções **inovadoras**, **éticas** e **eficazes**.

### Objetivos Específicos

1. 🔍 **Compreender** o impacto transformador da IA em cada fase do SDLC
2. 🛠️ **Desenvolver** habilidades técnicas para implementar ferramentas de IA
3. 🌐 **Explorar** aplicações práticas em cenários reais
4. 🧐 **Analisar criticamente** limitações, vieses e desafios éticos
5. ⚖️ **Fomentar** abordagem ética e responsável no uso de IA
6. 💻 **Aplicar** conhecimentos em projetos que simulem desafios reais
7. 📊 **Avaliar** qualidade e confiabilidade usando métricas apropriadas

---

## 🏆 Competências Esperadas

Ao concluir esta disciplina, os alunos deverão ser capazes de:

### 💻 Competências Técnicas

- Aplicar ferramentas de IA em diferentes fases do SDLC
- Implementar soluções que integrem LLMs em pipelines de desenvolvimento
- Utilizar assistentes de codificação (Copilot, Claude Code) de forma crítica
- Desenvolver e gerenciar pipelines CI/CD com componentes de IA
- Avaliar código gerado usando benchmarks (HumanEval, SWE-bench)

### 🧠 Competências Analíticas

- Analisar e interpretar criticamente resultados de sistemas de IA
- Avaliar implicações éticas, sociais e técnicas
- Identificar limitações, vieses e riscos
- Comparar abordagens tradicionais vs. assistidas por IA

### 👔 Competências Profissionais

- Colaborar efetivamente em projetos de equipe
- Comunicar ideias técnicas complexas com clareza
- Documentar soluções de forma profissional
- Apresentar resultados para audiências técnicas e não-técnicas

### 🚀 Competências de Inovação

- Desenvolver soluções criativas usando IA
- Propor melhorias em ferramentas e processos
- Explorar novas fronteiras em AI/SE

### ⚖️ Competências Éticas

- Aplicar princípios éticos no uso de IA
- Reconhecer e mitigar riscos éticos e sociais
- Atribuir corretamente uso de IA e respeitar propriedade intelectual

---

## 📚 Estrutura da Disciplina

A disciplina está organizada em **fases progressivas** que levam os alunos de fundamentos teóricos até a implementação de um projeto completo.

### 📅 Visão Geral

```
Aula 0              → Nivelamento e Setup
Aulas 1-7  (4 sem)  → Fundamentos + Mini-Projeto 1 (Requirements & Design)
Aulas 8-14 (4 sem)  → Development & Testing + Mini-Projeto 2
Aulas 15-21 (4 sem) → Maintenance & Ethics + Início do Projeto Final
Aulas 22-26 (3 sem) → Projeto: Movimento Composição (Design Técnico)
Aulas 27-32 (3 sem) → Projeto: Movimento Ensaio (Construção)
Aulas 33-36 (2 sem) → Projeto: Movimento Ressonância (Validação)
```

### 🎯 Destaques do Conteúdo

#### Aulas 1-15: Fundamentos e Mini-Projetos

- ✅ IA no SDLC: Requirements, Design, Architecture
- ✅ Desenvolvimento assistido por IA (Code generation, completion)
- ✅ Testes automatizados e DevOps com IA
- ✅ Manutenção, detecção de bugs e evolução de software
- ✅ 2 mini-projetos práticos com checkpoints

#### Aulas 16-36: Projeto Final com Metodologia Sinfonia

- 🎼 **4 Movimentos** estruturados com artefatos concretos
- 🎯 **2 Aulas Especiais:**
  - **Aula 22:** Prompt Engineering para ES (workshop intensivo)
  - **Aula 30:** Segurança, Vulnerabilidades e Hallucination
- 🎤 **2 Palestras Convidadas:**
  - **Aula 11:** Profissional da indústria (IA em produção)
  - **Aula 34:** Pesquisador acadêmico (avaliação de sistemas de IA)
- 📊 **4 Checkpoints** de avaliação

> 📅 **Cronograma completo:** Veja o [Planejamento Detalhado do Semestre corrente](./PLANEJAMENTO.md)

---

## 📊 Avaliação

A avaliação é **contínua**, **formativa** e **somativa**, refletindo diferentes aspectos do aprendizado.

### 💯 Distribuição de Notas

| Componente | Peso | Detalhes |
|------------|------|----------|
| **Participação e Mini-Projetos** | **25%** | Aulas 1-21 |
| • Presença e debates | 5% | Participação ativa |
| • Exercícios práticos | 15% | Hands-on em sala |
| • Mini-Projeto 1 (Checkpoint Aula 7) | 5% | Requirements & Design |
| **Projeto Final (Sinfonia)** | **75%** | Aulas 22-36 |
| • Checkpoint 1 - Exposição (Aula 21) | 10% | Estratégia e problema |
| • Checkpoint 2 - Composição (Aula 26) | 15% | Design técnico |
| • Checkpoint 3 - Ensaio (Aula 32) | 10% | MVP funcional |
| • Entrega Final (Aula 29) | 30% | Sistema + docs + análise |
| • Apresentação Final (Aulas 35-36) | 7% | Demo e defesa |
| • Contribuição Individual | 3% | Peer review + commits |

### ✅ Requisitos de Aprovação

- **Nota final:** ≥ 5,0 (escala 0-10)
- **Frequência:** ≥ 75% de presença
- **Participação obrigatória:** em todos os checkpoints
- **Entrega obrigatória:** projeto final + apresentação

### 📋 Critérios de Avaliação

**Projeto Final será avaliado em:**
- 🚀 Inovação e criatividade (20%)
- ⚙️ Funcionalidade e aplicação prática (25%)
- 💎 Qualidade técnica (código, arquitetura, testes) (20%)
- 📚 Documentação profissional (15%)
- 🧐 Análise crítica (limitações, ética, vieses) (10%)
- 🎤 Apresentação e comunicação (10%)

> ⚖️ **Integridade Acadêmica:** Todos os alunos devem aderir ao [Código de Conduta para Uso Ético de IA](./docs/Codigo_de_Conduta.md)

---

## 📁 Estrutura do Repositório

```
esaia/
├── README.md                          # Este arquivo
├── PLANEJAMENTO_2026_1.md            # Cronograma detalhado do semestre
├── LICENSE                            # Licença do repositório
│
├── docs/                              # Documentação principal
│   ├── Plano_de_Ensino.md            # Plano de ensino completo
│   ├── Codigo_de_Conduta.md          # Código de conduta para uso de IA
│   ├── FAQ.md                         # Perguntas frequentes
│   └── Glossario.md                   # Glossário de termos
│
├── aulas/                             # Material das aulas
│   ├── aula-00/                       # Nivelamento (pré-semestre)
│   ├── aula-01/                       # Introdução à ESAIA
│   ├── aula-02/                       # LLMs e IA Generativa
│   └── ...
│
├── mini-projetos/                     # Especificações dos mini-projetos
│   ├── mini-projeto-1/                # Requirements & Design
│   ├── mini-projeto-2/                # Development & Testing
│   └── mini-projeto-3/                # Maintenance & Evolution
│
├── projeto-final/                     # Projeto final (Sinfonia)
│   ├── templates/                     # Templates dos 14 artefatos
│   ├── rubricas/                      # Rubricas de avaliação
│   ├── exemplos/                      # Exemplos de projetos anteriores
│   └── README.md                      # Guia do projeto final
│
├── recursos/                          # Recursos adicionais
│   ├── ferramentas/                   # Guias de ferramentas (Copilot, etc.)
│   ├── tutoriais/                     # Tutoriais e HOWTOs
│   ├── datasets/                      # Datasets para exercícios
│   ├── benchmarks/                    # Informações sobre benchmarks
│   └── leituras/                      # Material de leitura complementar
│
├── avaliacoes/                        # Sistema de avaliação
│   ├── checkpoints/                   # Especificações dos checkpoints
│   └── criterios/                     # Critérios detalhados
│
└── semestres/                         # Histórico de semestres
    └── 2026-1/                        # Semestre atual
        ├── equipes/                   # Repositórios das equipes
        ├── palestras/                 # Material das palestras convidadas
        └── retrospectiva/             # Retrospectivas e feedback
```

---

## 🚀 Como Usar Este Repositório

### Para Alunos Matriculados

1. **⭐ Star** este repositório para acompanhar atualizações
2. **👀 Watch** para receber notificações de mudanças
3. **📚 Leia** o [Plano de Ensino](./docs/Plano_de_Ensino.md) completo
4. **⚖️ Assine** o [Código de Conduta](./docs/Codigo_de_Conduta.md) na primeira semana
5. **📅 Acompanhe** o [Planejamento do Semestre Corrente](./PLANEJAMENTO.md) semanalmente
6. **💬 Participe** do Discord/Slack da turma
7. **🔍 Explore** os materiais das aulas antes de cada encontro
8. **🤝 Colabore** com sua equipe no projeto final

### Para Visitantes e Curiosos

- Explore o conteúdo livremente (licença CC BY-NC-SA 4.0)
- Adapte materiais para suas próprias aulas (com atribuição)
- Entre em contato com sugestões e melhorias
- Contribua com pull requests (melhorias nos materiais)

### 📢 Atualizações e Comunicação

- **Anúncios importantes:** Issues com label `📢 announcement`
- **Dúvidas gerais:** Discussions do GitHub
- **Dúvidas específicas:** Discord/Slack da turma
- **Bugs/correções:** Issues com label `🐛 bug`
- **Sugestões:** Issues com label `💡 enhancement`

---

## 🛠️ Recursos Didáticos

### Ferramentas de IA

#### Assistentes de Codificação
- [GitHub Copilot](https://github.com/features/copilot) (licenças educacionais disponíveis)
- [Claude Code](https://claude.ai) (Anthropic)
- [Cursor AI](https://cursor.sh)
- [JetBrains AI Assistant](https://www.jetbrains.com/ai/)
- [Aider](https://github.com/paul-gauthier/aider) (CLI tool)
- [Continue.dev](https://continue.dev)

#### APIs de LLMs
- [OpenAI API](https://platform.openai.com/docs) (GPT-4, GPT-4 Turbo)
- [Anthropic API](https://docs.anthropic.com) (Claude 3.5 Sonnet, Claude 3 Opus)
- [Google Gemini API](https://ai.google.dev)

> 💡 **Acesso institucional** com créditos limitados será fornecido

### Benchmarks e Datasets

- **[HumanEval](https://github.com/openai/human-eval)** - Avaliação de geração de código Python
- **[SWE-bench](https://www.swebench.com)** - Resolução de issues reais do GitHub
- **[CodeXGLUE](https://github.com/microsoft/CodeXGLUE)** - Suite de tarefas para code understanding
- **[BigCodeBench](https://bigcode-bench.github.io/)** - Benchmark para code generation

### Ferramentas

- **GitHub Copilot** [Documentation](https://docs.github.com/en/copilot)
- **Claude Code** by Anthropic [Documentation](https://code.claude.com/docs/en/overview)
- **Claude API** [Docs](https://platform.claude.com/docs/en/home)
- **Cursor AI** [Documentation](https://cursor.com/docs)
- **Aider** [Documentation](https://aider.chat/docs/)
- **Continue.dev** [Documentation](https://docs.continue.dev/)
- **Antigravity** by Google [Documentation](https://antigravity.google/docs/get-started)

### Frameworks e Bibliotecas

- **[LangChain](https://python.langchain.com)** - Framework para aplicações com LLMs
- **[LlamaIndex](https://www.llamaindex.ai)** - Framework para RAG e data augmentation
- **[Hugging Face Transformers](https://huggingface.co/docs/transformers)** - Biblioteca de modelos
- **[OpenAI Cookbook](https://github.com/openai/openai-cookbook)** - Receitas e exemplos

### Plataformas e Infraestrutura

- **GitHub Education** - Repositórios privados e ferramentas gratuitas
- **Cloud Credits** - AWS Educate / Azure for Students / GCP Education
- **Docker** - Containerização e ambientes reproduzíveis

### Material de Leitura

Veja a seção completa de [Referências Bibliográficas](#referências-bibliográficas) ao final deste documento.

---

## 📞 Contato

### Professor

- **Nome:** Vinicius Cardoso Garcia
- **E-mail:** [vcg@cin.ufpe.br](mailto:vcg@cin.ufpe.br)
- **Website:** [viniciusgarcia.me](https://viniciusgarcia.me)
- **GitHub:** [@vinicius3w](https://github.com/vinicius3w)
- **Twitter/X:** [@vinicius3w](https://twitter.com/vinicius3w)
- **LinkedIn:** [viniciusgarcia](https://www.linkedin.com/in/viniciusgarcia/)

### Office Hours

- **Quando:** Segundas-feiras, 14h-16h (ou agendamento via e-mail)
- **Onde:** Sala do professor ou online (Google Meet/Zoom)
- **Agendamento:** E-mail com antecedência de 24 horas

### Canais da Disciplina

- **Discord/Slack:** *(Link será fornecido no início do semestre)*
- **GitHub Discussions:** [Discussões e Q&A](../../discussions)
- **E-mail da turma:** *(será criado no início do semestre)*

### Suporte

- **Dúvidas técnicas:** Discord/Slack da disciplina
- **Dúvidas administrativas:** E-mail do professor
- **Problemas com materiais:** Issues neste repositório
- **Sugestões de melhoria:** GitHub Discussions ou Issues

---

## 📚 Referências Bibliográficas

### 📖 Livros e Textos Fundamentais

1. **Russell, S., & Norvig, P.** (2020). *Artificial Intelligence: A Modern Approach* (4th ed.). Pearson. [Website](https://aima.cs.berkeley.edu/)

2. **Garcia, V. C., & Medeiros, R. P.** (2025). *Sinfonia: Orquestrando a Inteligência Artificial*. ASSERT Lab. [GitHub](https://github.com/assertlab/sinfonia)

### 📊 Surveys e Revisões Sistemáticas (2023-2024)

3. **Fan, A., et al.** (2023). Large Language Models for Software Engineering: Survey and Open Problems. *IEEE/ACM ICSE-FoSE*. [DOI](https://doi.org/10.1109/ICSE-FoSE59343.2023.00008)

4. **Belzner, L., Gabor, T. and Wirsing, M.** (2024) “Large Language Model Assisted Software Engineering: Prospects, Challenges, and a Case Study,” in Lecture Notes in Computer Science (including subseries Lecture Notes in Artificial Intelligence and Lecture Notes in Bioinformatics). Springer, Cham, pp. 355–374. [DOI](https://doi.org/10.1007/978-3-031-46002-9_23).

5. **Sauvola, J., et al.** (2024). Future of software development with generative AI. *Automation in Software Engineering*, 31. [DOI](https://doi.org/10.1007/s10515-024-00426-z)

6. **Wang, J., et al.** (2024). Software Testing With Large Language Models: Survey, Landscape, and Vision. *IEEE TSE*, 50(4), 911-936. doi: 10.1109/TSE.2024.3368208. Disponível em: <https://arxiv.org/abs/2307.07221v3>.

### 🔧 Requirements Engineering e Design

7. **Zhao, L., et al.** (2021). Natural language processing for requirements engineering: A systematic mapping study. *ACM CSUR*, 54(3), 1-41. <https://dl.acm.org/doi/10.1145/3444689>

8. **Salminen, J., et al.** (2021). “A Survey of 15 Years of Data-Driven Persona Development,” _International Journal of Human–Computer Interaction_, 37(18), pp. 1685–1708. Available at: <https://doi.org/10.1080/10447318.2021.1908670>.

9. **Zhang, X., et al.** (2023).“PersonaGen: A Tool for Generating Personas from User Feedback,” 2023 IEEE 31st International Requirements Engineering Conference (RE), 2023-Septe, pp. 353–354. Available at: <https://doi.org/10.1109/RE57278.2023.00048>.

### 🏗️ Software Architecture

10. **Esposito, M. et al.** (2026) “Generative AI for software architecture. Applications, challenges, and future directions,” Journal of Systems and Software, 231, p. 112607. Available at: <https://doi.org/10.1016/j.jss.2025.112607>.

11. **Bucaioni, A. et al.** (2025) “Artificial Intelligence for Software Architecture: Literature Review and the Road Ahead,” Proceedings of The ACM International Conference on the Foundations of Software Engineering (FSE ’25), 1. Available at: <https://arxiv.org/html/2504.04334v1>.

### 💻 Development, Code Generation, Testing

12. **Vijayvergiya, M., et al.** (2024). “AI-Assisted Assessment of Coding Practices in Modern Code Review.” Available at: <https://doi.org/10.1145/3664646.3665664>.

13. **Poldrack, R. A., et al.** (2023). “AI-assisted coding: Experiments with GPT-4.” Available at: <https://arxiv.org/pdf/2304.13187> (Accessed: January 28, 2026).

### 🚀 DevOps, CI/CD, Deployment

14. **Fu, M., et al.** (2024). “AI for DevSecOps: A Landscape and Future Opportunities,” arXiv preprint arXiv:2404.04839 [Preprint]. Available at: <https://arxiv.org/abs/2404.04839v1> (Accessed: May 27, 2024).

### 🐛 Maintenance, Bug Detection

15. **Ravikumar, C. et al.** (2025) “A Comprehensive Analysis of Machine Learning Methods for Bug Prediction in Software Development,” in Lecture Notes in Electrical Engineering. Springer, Singapore, pp. 929–935. Available at: <https://doi.org/10.1007/978-981-97-8031-0_99>.

16. **Sakib, F.F. et al.** (2025) “A Comprehensive Evaluation of Machine Learning Techniques for Predicting Software Bugs,” in 2025 4th International Conference on Robotics, Electrical and Signal Processing Techniques (ICREST). IEEE, pp. 228–233. Available at: <https://doi.org/10.1109/ICREST63960.2025.10914387>.

17. **Gazit, T.** (2024). Fixing security vulnerabilities with AI. *The GitHub Blog*. Available at: <https://github.blog/engineering/platform-security/fixing-security-vulnerabilities-with-ai/>. Updated April 7, 2025.

18. **Keller, J., & Nowakowski, J.** (2024). AI-powered patching: the future of automated vulnerability fixes. *Google Security Report*. Available at: <https://research.google/pubs/ai-powered-patching-the-future-of-automated-vulnerability-fixes/>

### ⚖️ Ética, Viés, Responsabilidade

19. **Ferrara, E.** (2023). “Fairness and Bias in Artificial Intelligence: A Brief Survey of Sources, Impacts, and Mitigation Strategies,” Sci, 6(1), p. 3. Available at: <https://doi.org/10.3390/sci6010003>.

20. **Wu, F., et al.** (2024). “A New Era in LLM Security: Exploring Security Concerns in Real-World LLM-based Systems.” Available at: <https://arxiv.org/pdf/2402.18649> (Accessed: January 28, 2026).

21. **Zhao, H., et al.** (2024). Explainability for large language models: A survey. *ACM TIST*, 15(2), 1-38.

### 🌐 Recursos Online e Documentação

22. **ACM Code of Ethics** (2024). [Link](https://www.acm.org/code-of-ethics)

23. **IEEE Ethically Aligned Design** (2024). [Link](https://standards.ieee.org/industry-connections/ec/ead/)

24. **GARCIA, Vinicius.** Transformação Digital com IA Series. [dev.to](https://dev.to/vinicius3w/series/32001)

25. **GARCIA, Vinicius.** Engenharia de Software Assistida por IA Series' Articles. [dev.to](https://dev.to/vinicius3w/series/34768)

26. **Anthropic Claude Documentation**. [Link](https://docs.anthropic.com/)

27. **OpenAI API Documentation**. [Link](https://platform.openai.com/docs)

28. **HuggingFace Transformers**. [Link](https://huggingface.co/docs/transformers/)

> 📚 **Referências completas:** Veja a lista completa de 45+ referências no [Plano de Ensino](./docs/Plano_de_Ensino.md)

---

## 📄 Licença

<div align="center">

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

Este trabalho está licenciado sob uma
[Licença Creative Commons Atribuição-NãoComercial-CompartilhaIgual 4.0 Internacional][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

**Você tem o direito de:**
- ✅ **Compartilhar** - copiar e redistribuir o material em qualquer suporte ou formato
- ✅ **Adaptar** - remixar, transformar e criar a partir do material

**Sob as seguintes condições:**
- 📝 **Atribuição** - Você deve dar o crédito apropriado
- 🚫 **Não Comercial** - Você não pode usar o material para fins comerciais
- 🔄 **Compartilha Igual** - Se você remixar, transformar ou criar a partir do material, deve distribuir suas contribuições sob a mesma licença

</div>

---

## 🙏 Agradecimentos

Esta disciplina foi desenvolvida com inspiração e contribuições de:

- **Rodrigo Pessoa Medeiros** - Co-criador da Metodologia Sinfonia
- **ASSERT Lab** - Laboratório de Pesquisa em Engenharia de Software
- **Alunos das turmas 2021-2024** - Feedback valioso para refinamento da Sinfonia
- **Comunidade Open Source** - Ferramentas e frameworks utilizados
- **Pesquisadores e autores** - Referências bibliográficas que fundamentam a disciplina

---

## 📝 Notas de Versão

### Versão 3.0 (Dezembro 2025) - Atual

- ✨ Integração completa da Metodologia Sinfonia
- ✨ Adição de aulas especiais: Prompt Engineering e Segurança de IA
- ✨ Estruturação completa do cronograma de projeto (Aulas 16-36)
- ✨ 14 artefatos concretos da Sinfonia mapeados
- ✨ Sistema de checkpoints alinhado aos 4 movimentos
- ✨ Inclusão de 2 palestras convidadas estrategicamente posicionadas
- ✨ Cobertura de tópicos críticos: hallucination, segurança, propriedade intelectual
- ✨ README aprimorado com navegação e recursos visuais

### Versão 2.0 (Novembro 2025)

- 📝 Criação do plano de ensino detalhado
- 📝 Definição de pré-requisitos e competências
- 📝 Estruturação das primeiras 15 aulas
- 📝 Sistema de avaliação com checkpoints

---

## 🔮 Próximas Atualizações

- [ ] Criação do arquivo `PLANEJAMENTO_2026_1.md` com cronograma interativo
- [ ] Templates dos 14 artefatos da Sinfonia
- [ ] Rubricas detalhadas de avaliação
- [ ] Material das aulas (slides, exercícios, exemplos)
- [ ] Setup de Discord/Slack da turma
- [ ] GitHub Organization para projetos
- [ ] Vídeos tutoriais de ferramentas
- [ ] Exemplos de projetos de semestres anteriores

---

<div align="center">

### 🚀 Bem-vindo à jornada de Engenharia de Software Assistida por IA!

**Perguntas?** Abra uma [Issue](../../issues) ou participe das [Discussions](../../discussions)

**Sugestões?** Pull Requests são bem-vindos!

---

**Made with ❤️ by CIn/UFPE**

**⭐ Star este repo para acompanhar atualizações**

</div>
