<p align="center">
  <img src="assets/banner.png" alt="F1 Strategic Financial Controller" width="100%">
</p>

<p align="center">
  Simulação de controladoria estratégica e alocação de teto orçamentário da Fórmula 1 (temporada 2026) estruturada com Engenharia de Prompt avançada.
</p>

<p align="center">
  <img alt="Prompt Engineering" src="https://img.shields.io/badge/IA-Prompt_Engineering-C52E36?style=for-the-badge">
  <img alt="IBM" src="https://img.shields.io/badge/Certifica%C3%A7%C3%A3o-IBM_Cognitive_Class-11120F?style=for-the-badge">
  <img alt="F1 2026" src="https://img.shields.io/badge/F1-Cost_Cap_2026-18181B?style=for-the-badge">
</p>

## Sobre o projeto

Sob o novo regulamento técnico e financeiro de **2026 da FIA**, uma equipe de Fórmula 1 precisa equilibrar investimentos em aerodinâmica ativa, unidades de potência híbridas, simuladores CFD e logística intercontinental sem ultrapassar o teto de gastos (*Cost Cap*) de **US\$ 145 milhões**.

Este projeto aplica frameworks estruturados de **Engenharia de Prompt** em Grandes Modelos de Linguagem (LLMs) para construir um controlador financeiro e estratégico de alta precisão. Em vez de aceitar respostas genéricas, a arquitetura de prompts força o modelo a coletar restrições reais, demonstrar cada cálculo passo a passo, comparar cenários concorrentes e auditar suas próprias recomendações.

## Principais metodologias aplicadas

| Metodologia | Como funciona no projeto |
|---|---|
| **Persona & Interview Pattern** | Configura a IA como CFO e Team Principal de F1, instruindo-a a entrevistar o usuário sobre pilotos, túnel de vento, CFD e motor antes de orçar. |
| **Chain-of-Thought (CoT)** | Exige raciocínio passo a passo na decomposição de custos de P&D, clusters de GPU e folha técnica dentro do limite de US\$ 145M. |
| **Tree-of-Thought (ToT)** | Explora três ramos estratégicos diante de problemas de arrasto aerodinâmico (chassi, software CFD ou túnel de vento) e seleciona o maior ROI. |
| **Critical Analysis Expert (CAE)** | Instancia um agente auditor ("advogado do diabo") que identifica riscos ocultos de inflação logística e cria reserva de contingência de US\$ 4M. |

## Tecnologias e frameworks

<p>
  <img alt="LLMs" src="https://img.shields.io/badge/Large_Language_Models-C52E36?style=flat-square">
  <img alt="Chain of Thought" src="https://img.shields.io/badge/Chain--of--Thought-11120F?style=flat-square">
  <img alt="Tree of Thought" src="https://img.shields.io/badge/Tree--of--Thought-C52E36?style=flat-square">
  <img alt="IBM Watsonx" src="https://img.shields.io/badge/IBM_Cognitive_Class-11120F?style=flat-square">
  <img alt="Markdown" src="https://img.shields.io/badge/Markdown-C52E36?style=flat-square&logo=markdown&logoColor=white">
</p>

- **Persona & Interview Pattern** (docs/prompts/sistema_persona.md) para levantamento estruturado de requisitos;
- **Raciocínio CoT e ToT** (docs/prompts/cot_raciocinio.md) para consistência matemática e tomada de decisão multicritério;
- **Auditoria Crítica CAE** (docs/prompts/critica_cae.md) para mitigação de riscos regulatórios junto à FIA.

## Arquitetura do fluxo decisório

`mermaid
flowchart LR
    A[Sistema Persona · CFO F1] --> B[Entrevista de Requisitos]
    B --> C[Chain-of-Thought · Orçamento P&D]
    C --> D[Tree-of-Thought · Cenários Técnicos]
    D --> E[Agente CAE · Auditoria de Risco]
    E --> F[Relatório Estratégico 2026]
`

## Certificações

<p align="center">
  <img src="docs/The-Art-Of-Prompt-Engineering.jpeg" width="48%" alt="The Art Of Prompt Engineering">
  <img src="docs/Prompt-Engineering-For-Everyone.jpeg" width="48%" alt="Prompt Engineering For Everyone">
</p>

## Estrutura do repositório

`	ext
f1-strategic-financial-controller/
├── assets/
│   ├── banner.png                                  Banner principal do projeto
│   └── project-animal.png                          Símbolo do guepardo
├── docs/
│   ├── prompts/
│   │   ├── sistema_persona.md                      Configuração da Persona CFO e Interview Pattern
│   │   ├── cot_raciocinio.md                       Prompts de Chain-of-Thought e cálculos
│   │   └── critica_cae.md                          Auditoria pelo Critical Analysis Expert
│   ├── relatorio_estrategico_2026.md               Plano financeiro consolidado e KPIs
│   ├── Prompt-Engineering-For-Everyone.jpeg        Certificado IBM
│   └── The-Art-Of-Prompt-Engineering.jpeg          Certificado IBM
└── README.md
`

## Como explorar

1. Leia os prompts modulares na pasta [docs/prompts/](docs/prompts) na ordem: sistema_persona.md → cot_raciocinio.md → critica_cae.md.
2. Consulte o documento final consolidado em [docs/relatorio_estrategico_2026.md](docs/relatorio_estrategico_2026.md) para ver o cronograma, a distribuição do teto orçamentário e os indicadores de performance (KPIs).

---

<p align="center"><sub>Estudo · construção · evolução</sub><br><a href="https://github.com/arthurlynow098">Perfil</a> · <a href="https://arthurentsev.vercel.app/">Portfólio</a> · <a href="https://www.linkedin.com/in/entsevarthur/">LinkedIn</a></p>
