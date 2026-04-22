# F1 Strategic Financial Controller (2026 Season e Regulations)

## Contexto do Projeto
Este repositório contém o projeto final desenvolvido para a conclusão do curso **Prompt Engineering para IA Generativa**. O objetivo central foi utilizar Modelos de Linguagem de Grande Escala (LLMs), através da plataforma **IBM Cognitive Class**, para simular a gestão estratégica e financeira de uma equipe de Fórmula 1 sob o novo regulamento técnico e financeiro de 2026.

O desafio consistiu em projetar um fluxo de trabalho que garantisse precisão matemática e visão crítica, respeitando o limite de teto de gastos da FIA, utilizando técnicas avançadas de engenharia de prompt para guiar a inteligência artificial.

## Metodologias e Engenharia de Prompt Aplicadas

Para elevar a qualidade das interações e evitar respostas genéricas, foram implementados os seguintes métodos apresentados no curso:

### 1. Persona e Interview Pattern
Em vez de solicitar um plano pronto, a IA foi configurada com a persona de um **CFO e Team Principal de F1**. Foi aplicado o *Interview Pattern* para que a IA assumisse o controle da coleta de requisitos.
* **Exemplo Prático:** A IA foi instruída a não gerar o orçamento antes de me entrevistar sobre quatro pilares: escolha de pilotos, infraestrutura de túnel de vento, foco em CFD e escolha e estrátegia de motor.

### 2. Chain-of-Thought (CoT)
Utilizado para garantir que os cálculos financeiros fossem logicamente consistentes. O modelo foi instruído a "pensar passo a passo" antes de apresentar números finais.
* **Exemplo Prático:** Ao calcular o investimento em Pesquisa e Desenvolvimento, conhecido como P&D, a IA primeiro discriminou os custos de infraestrutura de TI e clusters de GPU para simulações, justificou a alocação de pessoal e só então apresentou o montante final dentro do teto de US$ 145M.

### 3. Tree-of-Thought (ToT)
Aplicado para a resolução de problemas complexos que exigiam avaliação de múltiplos caminhos.
* **Exemplo Prático:** Diante de um problema de arrasto aerodinâmico no carro, a IA gerou três "rumos" de pensamento (redesenho de chassi, foco em software de simulação ou upgrade de túnel de vento), avaliou os prós e contras de cada caminho e selecionou a rota com melhor custo-benefício financeiro.

### 4. Sistema Nova (Critical Analysis Expert - CAE)
Implementação de um framework de agentes virtuais onde uma instância da IA atua como um "advogado do diabo" para criticar a estratégia proposta.
* **Exemplo Prático:** O agente CAE (Critical Analysis Expert) revisou o plano final e identificou um risco oculto de inflação logística em corridas intercontinentais, sugerindo um plano de contingência de US$ 4 milhões para evitar sanções da FIA.

## 📂 Estrutura do Repositório

* 📁 **`/prompts`**: Documentação de todos os comandos e instruções de sistema utilizados para configurar a IA (Persona, CoT, ToT e CAE).
* 📁 **`/docs`**: O **Relatório Estratégico da Temporada 2026**, contendo o cronograma de ações, marcos de controle de orçamento e KPIs de performance.

## Conclusão
Este projeto demonstra como a Engenharia de Prompt transforma modelos de linguagem em ferramentas de consultoria de alta precisão. Através da orquestração de diferentes técnicas, foi possível criar um plano de negócios de Fórmula 1 que é tecnicamente robusto, financeiramente viável e estrategicamente defensável.


*Projeto realizado para certificação no curso de Prompt Engineering para IA Generativa.*

