# Estudo de Caso: Loop – Aplicativo de Gestão de Compras e Economia

**O Problema:** Consumidores de classe média (30-50 anos) sofrem com compras impulsivas, esquecimento de itens essenciais e falta de controle financeiro após as compras.

**A Solução:** Um gestor de listas inteligente que compara preços em tempo real, ajudando a poupar até 30%.

## 1. Product Discovery e Estratégia (Sprints 1 e 2)
- **Público-Alvo:** Casais e jovens adultos que procuram economia e novas experiências.
- **Diferencial Competitivo:** Ao contrário de apps como Bring! ou Listonic, o Loop automatiza a comparação de preços entre lojas físicas e e-commerce.
- **North Star Metric:** Número de Usuários Ativos Semanais (WAU) que adicionam itens ou utilizam cupões.

## 2. Definição do Produto e Backlog (Sprints 3 e 4)
- **Mapeamento de Funcionalidades:** Utilização de User Story Mapping para dividir a jornada em Épicos (Cadastro, Gerenciamento de Listas, Monetização).
**OKRs de Negócio:**
  - **Crescimento:** Alcançar 10.000 utilizadores ativos e reduzir o abandono no cadastro em 30%.
  - **Receita:** Converter 5% da base em assinantes premium e lançar 2 funcionalidades pagas.
- **Refinamento:** Aplicação de critérios de aceite no formato Gherkin/BDD (Dado/Quando/Então) e as Sete Dimensões do Produto.

## 3. Execução e Gestão Ágil (Sprints 5, 6 e 7)
- **Ferramentas:** Uso do Azure DevOps para gestão do backlog tático e operacional.
- **Planeamento:** Estimativa de esforço por "tamanho de t-shirt" e definição de sprints de 7 dias para garantir um fluxo contínuo de entregas.
- **Papel do PO no Desenvolvimento:** Acompanhamento diário da equipa (Devs, BAs e Testers), gestão de imprevistos e foco na priorização das histórias de utilizador (ex: Prioridade A a Z).

## 4. Resultados de Produto e Lições Aprendidas (Sprint 8)
- **Métricas de Desempenho:** Acompanhamento da Taxa de Retenção, Tempo Médio de Sessão e Taxa de Conversão de Cliques em Cupões.
- **Roadmap Futuro:** Evolução para a Versão 3 (Março 2027) com foco em Automação e IA para antever a falta de itens e sugestões por geolocalização.

## 5. Análise do Fluxo de Trabalho (Sprint 6)
Na Sprint 6, o foco foi a gestão do fluxo contínuo e a alocação eficiente do time (Analistas de Negócio, Desenvolvedores e Testers).
- **Cadência e Sprints** O fluxo foi estruturado em iterações curtas de 7 dias. Isso permite uma resposta rápida a impedimentos e uma visibilidade constante do progresso.
- **Visibilidade do Dia a Dia:** Acompanhou-se o trabalho da equipe através do Azure DevOps, monitorando quem estava atuando em cada História de Usuário (HU) em dias específicos (ex: dias 16 ao 20).
- **Gargalos:** A análise do fluxo permitiu identificar onde as histórias ficavam retidas (se no desenvolvimento ou na fase de testes/validação pelos BAs).

## 6. A Proposta de Solução: Shifting Left (Sprint 8)
A abordagem "Shift-Left" apresentada na Sprint 8 propõe mover as atividades de teste e qualidade para o início do ciclo de desenvolvimento, em vez de deixá-las apenas para o final.
### **Cross-Training (Treinamento Cruzado)**
Desenvolvedores e analistas de negócio (BAs) também recebem treinamento em técnicas de teste. Se um Tester estiver ausente, a equipe não para.
### **Prevenção em vez de Detecção**
Ao envolver todos na escrita de critérios de aceite no formato BDD/Gherkin desde o refinamento, garante-se que o requisito seja testável antes mesmo de ser codificado.
### **Conformidade com Frameworks**
Utilização de referências de maturidade como o CMMI (Nível 3) e o MPT-BR (Melhoria do Processo de Teste Brasileiro).

## 7. Impacto Prático no Loop
Ao aplicar o Shifting Left e a análise de fluxo no desenvolvimento do app Loop, os resultados esperados são:
### **Redução de Bugs em Produção**
Validar a "Proposta de Valor" e os "Critérios de Aceite" (como os da tela de assinatura premium) logo no início.
### **Velocidade (Time-to-Market)**
Menos retrabalho significa que as funcionalidades do Roadmap (como a Versão 3 com IA) podem ser alcançadas com maior previsibilidade.
### **Qualidade de Software**
Garantia de que requisitos não funcionais, como o tempo de carregamento da tela em no máximo 3 segundos, sejam testados unitariamente pelos desenvolvedores.

**Resumo:** A análise das sprints mostra uma transição de um modelo de comando e controle para um modelo de qualidade compartilhada, onde o Product Owner garante que o fluxo de valor não seja interrompido por falhas que poderiam ter sido evitadas na fase de definição.
