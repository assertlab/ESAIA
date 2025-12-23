**UNIVERSIDADE FEDERAL DE PERNAMBUCO**

**CENTRO DE INFORMÁTICA (CIn)**

**BACHARELADO EM SISTEMAS DE INFORMAÇÃO (SI)**

---

# CÓDIGO DE CONDUTA PARA USO ÉTICO DE INTELIGÊNCIA ARTIFICIAL

## Disciplina: Engenharia de Software Assistida por IA (ESAIA) - IF0000

**Período:** 2026.1

**Professor:** Vinicius Cardoso Garcia (vcg@cin.ufpe.br)

**Versão:** 1.0 | **Data:** Janeiro 2026

---

## PREÂMBULO

Este Código de Conduta estabelece as diretrizes éticas e práticas para o uso de ferramentas de Inteligência Artificial (IA), incluindo Large Language Models (LLMs), assistentes de codificação e outras tecnologias relacionadas, no contexto da disciplina Engenharia de Software Assistida por IA.

O objetivo deste documento é:
1. Promover o uso responsável, ético e transparente de tecnologias de IA
2. Garantir a integridade acadêmica e o aprendizado genuíno dos alunos
3. Estabelecer expectativas claras sobre o que é aceitável e inaceitável
4. Preparar os alunos para práticas profissionais éticas na indústria
5. Fomentar uma cultura de responsabilidade e reflexão crítica

**Todos os alunos matriculados nesta disciplina devem ler, compreender e assinar este código de conduta na primeira semana de aula.** A violação deste código resultará em penalidades que podem incluir nota zero em trabalhos específicos, reprovação na disciplina, ou encaminhamento para a comissão disciplinar da universidade.

---

## PRINCÍPIOS FUNDAMENTAIS

### 1. INTEGRIDADE ACADÊMICA

A integridade acadêmica é a pedra angular da educação superior. Todos os alunos devem:
- Apresentar trabalho que reflita seu próprio entendimento e esforço
- Dar crédito apropriado a todas as fontes utilizadas, incluindo ferramentas de IA
- Nunca representar trabalho gerado por IA como sendo exclusivamente seu
- Ser honestos sobre o uso de ferramentas de IA em todos os trabalhos submetidos

### 2. TRANSPARÊNCIA

A transparência sobre o uso de IA é essencial para a confiança e o aprendizado:
- Documentar quando, onde e como ferramentas de IA foram utilizadas
- Explicar o papel da IA no processo de desenvolvimento
- Não ocultar ou minimizar a contribuição de ferramentas de IA
- Compartilhar prompts significativos e interações com LLMs quando relevante

### 3. RESPONSABILIDADE

Os alunos são responsáveis por todo o trabalho que submetem:
- Compreender completamente qualquer código ou texto gerado por IA
- Validar a correção, qualidade e adequação de outputs de IA
- Assumir responsabilidade por erros, bugs ou problemas éticos em código gerado por IA
- Reconhecer que a IA é uma ferramenta auxiliar, não um substituto para o pensamento crítico

### 4. APRENDIZADO GENUÍNO

O uso de IA deve promover, não substituir, o aprendizado:
- Usar IA para aprofundar compreensão, não para evitar aprender
- Engajar criticamente com outputs de IA ao invés de aceitá-los passivamente
- Desenvolver habilidades fundamentais de programação e engenharia de software
- Buscar entender "por que" e "como", não apenas "o que"

### 5. RESPEITO E COLABORAÇÃO

Manter um ambiente de aprendizado respeitoso e colaborativo:
- Colaborar eticamente com colegas de equipe
- Dar e receber feedback construtivo
- Respeitar a propriedade intelectual de outros (colegas, autores, criadores)
- Promover uma cultura de honestidade e suporte mútuo

---

## DIRETRIZES DE USO DE IA

### ✅ USO PERMITIDO E ENCORAJADO

As seguintes práticas são **permitidas e encorajadas** nesta disciplina:

#### 1. Assistência à Compreensão

- **Explicações de conceitos:** Pedir a LLMs para explicar conceitos de programação, algoritmos, ou engenharia de software que você não entende completamente.
  - *Exemplo:* "Explique como funciona o algoritmo de Dijkstra passo a passo."

- **Esclarecimento de dúvidas:** Usar IA para esclarecer sintaxe, semântica de linguagens de programação, ou funcionamento de APIs.
  - *Exemplo:* "Qual é a diferença entre `async` e `await` em JavaScript?"

- **Debugging assistido:** Pedir ajuda para entender mensagens de erro ou identificar possíveis causas de bugs.
  - *Exemplo:* "Por que estou recebendo um `NullPointerException` nesta linha de código?"

#### 2. Geração de Código Auxiliar

- **Boilerplate code:** Gerar código repetitivo e padronizado (ex: getters/setters, configurações básicas, imports padrão).
  - *Exemplo:* Gerar a estrutura básica de uma classe Java com construtor, getters e setters.

- **Code completion:** Usar ferramentas como GitHub Copilot para autocompletar linhas de código durante a programação.
  - *Importante:* Revisar e entender todas as sugestões antes de aceitar.

- **Refatoração:** Solicitar sugestões de refatoração para melhorar legibilidade, performance ou manutenibilidade.
  - *Exemplo:* "Sugira uma refatoração para este método que tem complexidade ciclomática alta."

#### 3. Testes e Qualidade

- **Geração de casos de teste:** Usar IA para gerar unit tests, integration tests ou edge cases.
  - *Exemplo:* "Gere casos de teste para esta função que calcula o fatorial de um número."

- **Code review:** Solicitar que IA revise seu código e identifique possíveis melhorias ou problemas.
  - *Exemplo:* "Revise este código e identifique possíveis code smells ou violações de princípios SOLID."

#### 4. Documentação

- **Comentários e docstrings:** Usar IA para gerar comentários explicativos ou docstrings para funções complexas.
  - *Importante:* Revisar e ajustar para garantir precisão e clareza.

- **README e documentação técnica:** Obter assistência na estruturação e escrita de documentação, mas sempre revisar e personalizar.

#### 5. Pesquisa e Aprendizado

- **Exploração de bibliotecas e frameworks:** Pedir exemplos de uso de bibliotecas ou frameworks que você está aprendendo.
  - *Exemplo:* "Mostre um exemplo de como usar pandas para ler e processar um arquivo CSV."

- **Comparação de abordagens:** Solicitar comparações entre diferentes soluções ou tecnologias.
  - *Exemplo:* "Quais são as vantagens e desvantagens de usar REST vs GraphQL para uma API?"

#### 6. Iteração e Refinamento

- **Melhoria incremental:** Usar IA para iterar sobre suas próprias soluções, buscando melhorias.
  - *Processo recomendado:* Desenvolver uma primeira versão sozinho → Pedir feedback da IA → Refinar com base no feedback

---

### ❌ USO PROIBIDO

As seguintes práticas são **estritamente proibidas** e constituem violação do código de conduta:

#### 1. Substituição Completa do Trabalho

- **Geração completa de projetos:** Pedir à IA para gerar um projeto inteiro ou grandes partes sem contribuição significativa sua.
  - *Exemplo proibido:* "Crie um sistema completo de gerenciamento de biblioteca com todas as funcionalidades."

- **Cópia direta sem compreensão:** Copiar código gerado por IA sem entender o que cada linha faz ou como o código funciona.

- **Submissão de código não validado:** Submeter código gerado por IA que você não testou, revisou ou validou.

#### 2. Falta de Atribuição

- **Não documentar uso de IA:** Submeter trabalhos que usaram IA de forma significativa sem mencionar ou documentar esse uso.

- **Reivindicar autoria exclusiva:** Apresentar código ou texto gerado predominantemente por IA como sendo inteiramente de sua autoria.

- **Omitir ferramentas utilizadas:** Não listar ferramentas de IA utilizadas na seção de reconhecimentos ou documentação do projeto.

#### 3. Uso Antiético

- **Geração de código malicioso:** Usar IA para criar malware, exploits, ou código com intenções maliciosas.

- **Plagiarismo de colegas via IA:** Usar IA para gerar código muito similar ao de colegas e submeter como próprio.

- **Bypass de restrições:** Usar IA para contornar limitações intencionais da disciplina (ex: usar IA quando explicitamente proibido em um exercício específico).

#### 4. Violação de Propriedade Intelectual

- **Uso indevido de código protegido:** Usar IA para reproduzir código de projetos proprietários ou com licenças restritivas.

- **Violação de licenças:** Usar IA para gerar código que viola licenças de software (ex: reproduzir código GPL sem aderir à licença).

#### 5. Avaliações e Exames

- **Uso em avaliações individuais:** Usar IA em provas, quizzes, ou exercícios marcados como "sem assistência de IA" ou "individual sem ferramentas".

- **Compartilhamento de soluções geradas por IA:** Compartilhar com colegas soluções geradas por IA para trabalhos individuais.

---

## DOCUMENTAÇÃO OBRIGATÓRIA DO USO DE IA

### Quando Documentar

Você **deve documentar** o uso de IA quando:
1. IA gerou mais de 5 linhas consecutivas de código que você manteve no trabalho final
2. IA influenciou significativamente decisões de design, arquitetura ou implementação
3. IA foi usada para gerar casos de teste, documentação ou análises críticas
4. O professor ou instruções do trabalho explicitamente pedirem documentação de uso de IA

### Como Documentar

#### Em Código Fonte

Use comentários claros e específicos:

```python
# AI-GENERATED: GitHub Copilot
# Prompt: "Implement binary search for a sorted array"
# Date: 2026-03-15
# Note: Reviewed and validated. Modified loop condition for clarity.
def binary_search(arr, target):
    left, right = 0, len(arr) - 1
    while left <= right:
        mid = (left + right) // 2
        if arr[mid] == target:
            return mid
        elif arr[mid] < target:
            left = mid + 1
        else:
            right = mid - 1
    return -1
```

#### Em README / Documentação

Inclua uma seção dedicada:

```markdown
## Ferramentas de IA Utilizadas

### GitHub Copilot
- **Versão:** VS Code Extension v1.150.0
- **Uso:** Autocompletar código, gerar boilerplate para classes de modelo
- **Extensão do uso:** ~15% do código total (principalmente estrutura inicial)
- **Validação:** Todo código foi revisado, testado e ajustado conforme necessário

### GPT-4 (OpenAI API)
- **Uso:** Geração de casos de teste para módulo de autenticação
- **Prompts principais:** 
  - "Generate unit tests for user authentication with edge cases"
  - "Suggest integration tests for login flow"
- **Contribuição:** Gerou estrutura inicial de 20 test cases, dos quais 15 foram mantidos após revisão

### Claude 3.5 Sonnet (Anthropic)
- **Uso:** Análise de code smells e sugestões de refatoração
- **Output:** Identificou 8 code smells, dos quais 5 foram refatorados
```

#### Em Relatórios e Documentos

Adicione uma seção de "Reconhecimentos" ou "Metodologia":

```markdown
## Reconhecimentos

Este projeto utilizou ferramentas de assistência de IA para acelerar desenvolvimento:
- **GitHub Copilot** para code completion e geração de boilerplate
- **GPT-4** para brainstorming de arquitetura e geração de testes
- **Claude Code** para refatoração e análise de qualidade

Todo código gerado por IA foi cuidadosamente revisado, testado e validado 
pelo autor. As decisões de design e implementação foram tomadas pelo autor 
com base em compreensão dos conceitos da disciplina.
```

---

## BOAS PRÁTICAS PARA USO RESPONSÁVEL DE IA

### 1. Abordagem "AI as Co-Pilot, Not Pilot"

Trate a IA como um **assistente junior** que trabalha sob sua supervisão:
- Você é o arquiteto e tomador de decisões
- A IA oferece sugestões e executa tarefas repetitivas
- Você valida, refina e aprova todo output

### 2. Ciclo de Validação

Para qualquer código gerado por IA, siga este ciclo:

```
1. GERAR → 2. COMPREENDER → 3. TESTAR → 4. REFINAR → 5. VALIDAR → 6. DOCUMENTAR
```

**Perguntas críticas para fazer:**
- Entendo o que cada linha deste código faz?
- Este código atende aos requisitos corretamente?
- Existem edge cases não cobertos?
- O código segue boas práticas e padrões da linguagem?
- Há vulnerabilidades de segurança ou problemas de performance?

### 3. Prompt Engineering Eficaz

Para obter melhores resultados de IA:
- Seja específico e detalhado nos prompts
- Forneça contexto adequado
- Especifique requisitos não-funcionais (performance, segurança, legibilidade)
- Peça explicações, não apenas código
- Itere: refine o prompt se o resultado não for satisfatório

**Exemplo de prompt eficaz:**

❌ **Ruim:** "Crie uma função de ordenação"

✅ **Bom:** "Implemente o algoritmo QuickSort em Python para ordenar uma lista de inteiros. O código deve: (1) incluir comentários explicativos, (2) lidar com listas vazias e com um elemento, (3) usar particionamento in-place para economizar memória. Explique a complexidade de tempo e espaço."

### 4. Desenvolvimento Incremental

Não use IA para gerar grandes blocos de código de uma vez:
- Desenvolva incrementalmente, módulo por módulo
- Use IA para partes específicas, depois integre manualmente
- Mantenha controle total da arquitetura e design

### 5. Aprendizado Contínuo

Use IA como ferramenta de aprendizado:
- Quando a IA gerar código, estude-o e entenda por que funciona
- Pesquise conceitos desconhecidos que aparecem no código gerado
- Experimente modificar o código para ver o impacto
- Compare diferentes soluções propostas pela IA

### 6. Revisão Crítica

Sempre questione e valide outputs de IA:
- IA pode alucinar (gerar código incorreto com confiança)
- IA pode usar APIs obsoletas ou inexistentes
- IA pode não considerar contexto específico do seu projeto
- IA pode introduzir vieses ou vulnerabilidades

---

## CENÁRIOS E EXEMPLOS

### Cenário 1: Exercício de Programação Individual ✅

**Situação:** Você está resolvendo um exercício de implementação de árvore binária.

**Uso apropriado:**
1. Implementar a estrutura básica da árvore manualmente
2. Usar Copilot para autocompletar métodos auxiliares simples (getters, setters)
3. Pedir ao GPT-4 para explicar como funciona a rotação de árvores AVL
4. Gerar casos de teste com IA, mas revisar e adicionar casos próprios

**Documentação:**
```python
# AI-ASSISTED: GitHub Copilot para autocomplete em métodos auxiliares
# GPT-4 consultado para entender rotações AVL
# Implementação principal e lógica de balanceamento: autoria própria
```

---

### Cenário 2: Projeto em Equipe ✅

**Situação:** Seu grupo está desenvolvendo um sistema de gerenciamento de tarefas.

**Uso apropriado:**
1. Usar IA para gerar boilerplate de configuração (ex: setup de banco de dados)
2. Solicitar sugestões de design patterns apropriados para o problema
3. Gerar estrutura inicial de testes end-to-end
4. Usar IA para code review e identificação de code smells

**Documentação:** Adicionar seção "AI Tools" no README do projeto com detalhes completos.

---

### Cenário 3: Debugging de Problema Complexo ✅

**Situação:** Você está recebendo um erro estranho que não consegue resolver.

**Uso apropriado:**
1. Copiar a mensagem de erro e contexto relevante para um LLM
2. Pedir explicação do erro e possíveis causas
3. Solicitar estratégias de debugging
4. Implementar as soluções sugeridas, testando cada uma
5. Documentar a solução e o processo no commit message ou comentários

---

### Cenário 4: Aprendizado de Nova Tecnologia ✅

**Situação:** Você precisa usar uma biblioteca Python que nunca usou antes (ex: pandas).

**Uso apropriado:**
1. Pedir exemplos básicos de uso da biblioteca
2. Solicitar explicação de conceitos-chave (ex: DataFrames)
3. Gerar código de exemplo para operações comuns
4. Modificar e experimentar com os exemplos para solidificar aprendizado

---

### Cenário 5: Violação - Trabalho Completo por IA ❌

**Situação:** Você está sem tempo e pede à IA para gerar todo o projeto.

**Por que é proibido:**
- Não há aprendizado genuíno
- Você não será capaz de defender ou explicar o código
- Viola integridade acadêmica
- Prejudica seu próprio desenvolvimento profissional

**Consequência:** Nota zero no trabalho + possível reprovação na disciplina.

---

### Cenário 6: Violação - Falta de Atribuição ❌

**Situação:** Você usa extensivamente IA para gerar código, mas não documenta isso.

**Por que é proibido:**
- Falta de transparência
- Representação enganosa de autoria
- Impede avaliação justa pelo professor
- Viola princípio de integridade acadêmica

**Consequência:** Penalidade a ser determinada pelo professor, podendo incluir nota zero.

---

## DETECÇÃO E CONSEQUÊNCIAS

### Como o Professor Pode Detectar Uso Inadequado de IA

1. **Análise de código:**
   - Mudanças súbitas de estilo de codificação
   - Uso de padrões ou bibliotecas não ensinadas na disciplina
   - Código com complexidade desproporcional ao nível do aluno
   - Presença de comentários ou variáveis em inglês quando aluno sempre programa em português

2. **Avaliação de compreensão:**
   - Perguntas diretas sobre implementação durante checkpoints
   - Solicitação de explicação de decisões de design
   - Pedido de modificação ao vivo de partes do código

3. **Inconsistências:**
   - Discrepância entre qualidade de trabalhos e desempenho em sala
   - Código muito similar entre alunos
   - Falta de histórico de commits consistente no GitHub

4. **Ferramentas de detecção:**
   - Análise de padrões linguísticos típicos de LLMs
   - Comparação com corpus de código gerado por IA
   - Verificação de "assinaturas" de ferramentas específicas

### Processo de Investigação

Se houver suspeita de violação:
1. Aluno será convocado para reunião individual
2. Será solicitado que explique o código e decisões de implementação
3. Pode ser pedido que faça modificações ao vivo ou resolva problemas relacionados
4. Aluno tem direito de defesa e de apresentar documentação

### Consequências de Violações

**Primeira violação menor** (ex: falta de documentação de uso de IA):
- Advertência formal
- Dedução de pontos no trabalho específico (10-20%)
- Obrigação de refazer com documentação apropriada

**Violação moderada** (ex: uso extensivo não documentado):
- Nota zero no trabalho específico
- Advertência formal registrada
- Reunião com professor para discussão

**Violação grave** (ex: submissão de trabalho inteiramente gerado por IA sem contribuição):
- Nota zero no trabalho
- Possível nota zero na disciplina (reprovação)
- Encaminhamento para comissão disciplinar da universidade

**Violações repetidas:**
- Tratadas com severidade crescente
- Podem resultar em reprovação automática na disciplina
- Encaminhamento para comissão disciplinar

### Circunstâncias Atenuantes

Serão consideradas:
- Confusão genuína sobre regras (especialmente no início do semestre)
- Primeira ofensa de natureza menor
- Demonstração de aprendizado e correção voluntária
- Circunstâncias pessoais excepcionais (a critério do professor)

---

## RECURSOS E SUPORTE

### Se Você Tiver Dúvidas

- **Durante aulas:** Pergunte ao professor abertamente
- **Office hours:** Quintas-feiras, 14h-16h
- **Discord/Slack da disciplina:** Poste dúvidas no canal #etica-e-ia
- **E-mail:** vcg@cin.ufpe.br (resposta em 24-48h úteis)

### Recursos Adicionais

- **ACM Code of Ethics:** https://www.acm.org/code-of-ethics
- **IEEE Ethics Guidelines:** https://www.ieee.org/about/corporate/governance/p7-8.html
- **Artigos da disciplina:** Seção sobre ética e responsabilidade
- **Tutoriais:** Disponíveis no repositório GitHub da disciplina

### Reportando Violações

Se você testemunhar uma violação deste código por outro aluno:
- Você pode (mas não é obrigado a) reportar ao professor
- Reports podem ser anônimos através de formulário online
- Não há penalidade por reportar de boa-fé
- Há proteção contra retaliação

---

## CONCORDÂNCIA E ASSINATURA

Ao assinar este documento, eu declaro que:

✓ Li e compreendi completamente este Código de Conduta

✓ Concordo em seguir todas as diretrizes e princípios aqui estabelecidos

✓ Entendo que o uso de IA deve ser transparente, ético e voltado ao aprendizado

✓ Reconheço que sou responsável por todo trabalho que submeto, mesmo quando assistido por IA

✓ Compreendo as consequências de violações deste código

✓ Comprometo-me a usar IA de forma que promova meu aprendizado e desenvolvimento profissional

✓ Aceito que o professor pode solicitar explicações sobre qualquer trabalho submetido

---

**Nome Completo do Aluno:** _______________________________________________

**Matrícula:** _______________________________________________

**E-mail Institucional:** _______________________________________________

**Data:** ____/____/2026

**Assinatura:** _______________________________________________

---

## DECLARAÇÃO DO PROFESSOR

Como professor desta disciplina, comprometo-me a:
- Aplicar este código de forma justa e consistente
- Fornecer orientação clara sobre uso apropriado de IA
- Estar disponível para esclarecer dúvidas
- Avaliar trabalhos com justiça, considerando o uso documentado de IA
- Proteger a integridade acadêmica enquanto incentivo a inovação

**Professor:** Vinicius Cardoso Garcia

**Assinatura:** _______________________________________________

**Data:** ____/____/2026

---

## NOTAS FINAIS

Este código de conduta pode ser revisado e atualizado durante o semestre se necessário. Quaisquer mudanças serão comunicadas com antecedência e exigirão nova assinatura dos alunos.

**Versão atual:** 1.0 | **Data de vigência:** Janeiro 2026

**Última revisão:** Dezembro 2025

---

**Para discussões e feedback sobre este código, os alunos são encorajados a participar do canal #etica-e-ia no Discord/Slack da disciplina.**

---

*"A tecnologia é melhor quando aproxima as pessoas." - Matt Mullenweg*

*"Com grandes poderes vêm grandes responsabilidades." - Uncle Ben (Spider-Man)*

**Use IA com sabedoria. Aprenda genuinamente. Cresça eticamente.**
