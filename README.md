# Portfolio Product Owner
Portfólio de Product Owner (PO) com estudos de caso e aplicações práticas. Este repositório é uma demonstração prática de como eu executo as responsabilidades de um PO: Estratégia de Produto, Roadmap de Produto, Gestão de Backlog, Priorização, Refinamento, Criação de Histórias de Usuário e Visão de Produto. Projetos desenvolvidos como simulações para aprendizado.

## 1 - Aplicativo de Gerenciamento de Lista de Compras - MENTORIA PPL – CANAL VALOR (Agosto de 2025 – Dezembro de 2025)

Formação completa e especializada para atuar como **Product Owner / Product Manager**, com foco na gestão estratégica, tática e operacional de todo o ciclo de vida do produto, desde a Descoberta (Discovery) até a entrega e otimização por métricas.

* **Duração:** 150 horas de conteúdo prático e intensivo, concluídas em 150 dias.

---

### 🔑 Principais Habilidades e Competências Adquiridas

| Área de Atuação | Habilidades Desenvolvidas |
| :--- | :--- |
| **Estratégia e Descoberta de Produto (Product Discovery)** | **Mapeamento de Usuário:** Criação de Personas, Jornadas de Usuário e identificação aprofundada de dores e oportunidades de melhoria (Product Discovery).<br>**Definição Estratégica:** Criação da Visão do Produto, definição de Proposta de Valor Única, North Star Metric e estabelecimento de OKRs de Produto. |
| **Gestão e Priorização de Backlog** | **Roadmap e Backlog:** Criação do Product Roadmap e estruturação completa do Backlog (Épicos, Features e User Stories) do zero.<br>**Priorização e Refinamento:** Aplicação de técnicas de priorização e domínio do processo de Refinamento (Detalhar, Avaliar e Priorizar - Método DAP), incluindo definição de Critérios de Aceite (Gherkin/BDD) e uso de ferramentas de IA para refinamento. |
| **Entrega do Produto (Product Delivery)** | **Planejamento:** Definição do processo de planejamento, técnicas de estimativa e dimensionamento da capacidade do time (Capacity Planning).<br>**Monitoramento e Qualidade:** Gestão do ciclo de desenvolvimento, participação estratégica nos ritos (Daily), gestão de dependências, controle de fluxo de trabalho e validação das entregas (DoR e DoD: Definition of Ready/Done). |
| **Métricas e Otimização** | **Validação:** Condução da revisão e validação das demandas desenvolvidas com as partes interessadas (Stakeholders), garantindo a qualidade e aderência aos Critérios de Aceite.<br>**Métricas de Eficiência:** Análise e aplicação de métricas cruciais para a previsibilidade da entrega, incluindo Lead Time, Client Lead Time, Throughput, CFD (Cumulative Flow Diagram), WIP (Work In Progress) e CoD (Cost of Delay). |

---

### 🛠️ Experiência Prática e Ferramentas

* **Projeto Integrado:** Gestão de um produto digital utilizando o **PLMS (Product Leader Management System)**, um sistema completo de gestão de produtos desenvolvido no programa.
* **Formato Sprint:** Aprendizado dividido em 8 Sprints práticos, simulando o ciclo de desenvolvimento em um ambiente ágil.
* **Networking:** Construção de uma poderosa rede de contatos com gestores e líderes atuantes no mercado.

## 2 - Hub de Gerenciamento de Assinaturas (Case FinTech) — [Adolfo Lacerda](https://www.linkedin.com/in/adolfolacerda/) (Janeiro de 2026)

Estudo de caso focado em resolver a dor de **70% dos clientes** que possuem múltiplas assinaturas e perdem prazos de renovação. O desafio exigiu a transformação de uma visão tecnicamente inviável (sem APIs de cancelamento direto) em um **MVP funcional e valioso** em apenas 9 semanas (3 Sprints). O portfólio inclui uma apresentação e um texto justificando as decisões de produto.

### 🎯 O Desafio de Negócio
O plano original previa um "Botão Mágico" de cancelamento direto, impossível no momento por falta de APIs públicas e pela presença de dados transacionais "sujos". A estratégia foi pivotar para um hub de gerenciamento e controle financeiro.

### 🚀 Estratégia de MVP (Priorização Cruel)
Priorizei funcionalidades que atacam a visibilidade e o controle financeiro:

* **Radar de Assinaturas:** Dashboard que exibe o gasto total mensal e identifica transações recorrentes via *Whitelists* (Ethoca/Visa) para limpar o ruído de compras parceladas.
* **Notificações Antecipadas (Alerta Anti-Surpresa):** Alertas via Push, E-mail e WhatsApp 7 e 2 dias antes da renovação, resolvendo a dor do esquecimento.
* **Guias de Cancelamento:** Passo a passo manual para os serviços mais comuns, com potencial de alcançar até 98% de sucesso sem dependência de APIs.

### ✂️ Gestão de Backlog e Corte de Escopo (Versão 2)
* **Leitura de E-mails:** Descartada devido à complexidade técnica (parsing de texto variável), barreiras de segurança e tempo incompatível com o prazo.
* **Botão de Deep Linking:** Postergado por possuir valor menor para o usuário comparado aos guias detalhados de cancelamento.

### 📝 Especificação (Mão na Massa)
Foquei na especificação da funcionalidade **Radar de Assinaturas**:
* **User Story:** "Como um cliente que possui múltiplas assinaturas, eu quero visualizar uma lista clara das minhas cobranças recorrentes confirmadas pelo banco ou por mim, para que eu tenha controle total sobre minhas despesas e saiba exatamente o que será debitado no próximo mês.".
* **Critério de Aceite (Gherkin):** Inclui o cenário de correção de falso positivo pelo usuário ("Isto não é uma assinatura"), alimentando um loop de Machine Learning.

### 📊 Métricas de Sucesso
* **KPI Principal:** Engajamento com Notificações (Taxa de abertura/acesso ao Hub). Valida se a informação de renovação é útil e relevante.
* **Health Metric:** Taxa de Rejeição (Feedback Loop). Mede a precisão das *Whitelists* e a confiabilidade dos dados apresentados ao cliente.
