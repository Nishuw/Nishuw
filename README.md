<div align="center">

# Ryan Nishikawa

### Desenvolvedor de IA | Agentes Autônomos | Integração de Dados

Construo sistemas de IA que saem do chat e viram ferramenta de verdade: agentes com memória e controle real sobre desktop/terminal, pipelines de RAG sobre documentos complexos, e integrações que conectam LLMs a APIs e regras de negócio.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-ryan--nishikawa-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ryan-nishikawa)
[![GitHub](https://img.shields.io/badge/GitHub-Nishuw-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Nishuw)

</div>

---

## Sobre

Comecei em infraestrutura de redes, passei por RPA e cheguei em desenvolvimento de IA — hoje como Desenvolvedor(a) SR de IA na **Seidor**. Antes disso, RPA na Mix Fiscal e desenvolvimento/automação de redes na Global Hitss, sempre em Campinas/SP.

Meu foco é IA aplicada: pegar um problema mal definido (uma nota fiscal complexa, um fluxo de aprovação, uma dúvida recorrente de negócio) e transformar em sistema que roda, tem memória e pode ser melhorado com o tempo — não só um wrapper de prompt.

## Foco atual

- Agentes autônomos com memória persistente em camadas (curto e longo prazo) e controle direto de desktop/terminal
- RAG e extração de informação sobre documentos financeiros/fiscais complexos (PDFs com tabelas, gráficos vetoriais, regras fiscais)
- Orquestração multi-agente (orquestrador + sub-agentes) para automações de negócio
- Plataformas de teste/homologação de API com camada de explicação para público técnico e não técnico

---

## Stack

<div align="center">

**IA / Agentes**

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge)
![CrewAI](https://img.shields.io/badge/CrewAI-FF6F00?style=for-the-badge)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![MCP](https://img.shields.io/badge/Model_Context_Protocol-000000?style=for-the-badge)
![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![OpenRouter](https://img.shields.io/badge/OpenRouter-6366F1?style=for-the-badge)

**Dados**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-3776AB?style=for-the-badge)
![PyMuPDF](https://img.shields.io/badge/PyMuPDF-2C2C2C?style=for-the-badge)
![pdfplumber](https://img.shields.io/badge/pdfplumber-2C2C2C?style=for-the-badge)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Zustand](https://img.shields.io/badge/Zustand-433E38?style=for-the-badge)

**Ferramentas**

![Cursor](https://img.shields.io/badge/Cursor-000000?style=for-the-badge)
![Lovable](https://img.shields.io/badge/Lovable-FF66B2?style=for-the-badge)

</div>

---

## Projetos selecionados

### Tyrel
Assistente pessoal de IA para desktop, com interface visual própria (nós e conexões que evoluem conforme o sistema aprende), TTS via Kokoro-82M e sistema de skills adaptativo com onboarding e aprendizado contínuo a partir de histórico de chat. Memória persistente em duas camadas (`agent_memory_base.json` + `agent_memory_dynamic.json`) e controle direto de desktop.

`Tech: memória em camadas · TTS · sistema de skills · controle de desktop`

### TRON / agent_tron
Agente autônomo de desktop focado em execução: controle de filesystem e terminal, mesmo esquema de memória em duas camadas do Tyrel, sistema de skills/discoveries. Implementação CLI, orquestrado via Claude Opus.

`Tech: CLI · filesystem/terminal control · memória em camadas`

### DocRAG BR
Construído sozinho, remoto, na RAISE Summit Hackathon (Paris). RAG para empresas brasileiras processarem PDFs financeiros complexos (texto, tabelas, gráficos vetoriais) via chat. Camada de auditoria numérica que confere cada número da resposta contra o documento fonte, grounding visual com citação de página, e Vision LLM para gráficos vetoriais.
→ [github.com/Nishuw/DocRAG-BR](https://github.com/Nishuw/DocRAG-BR)

`Tech: PyMuPDF · pdfplumber · ChromaDB · OpenRouter`

### Circuito de Integração (Mix Fiscal)
Plataforma de testes de integração de API para o ambiente sandbox/homologação da Mix Fiscal. 16 endpoints (6 GETs sempre liberados, 10 POSTs com dependência sequencial), com explicação dupla — "pro negócio" e "pro dev" — de conceitos fiscais (ICMS, PIS/COFINS, NCM/CEST, CST, CFOP, MVA).

`Tech: Zustand · interpretador de respostas em PT-BR · export em PDF via jsPDF`

---

## Como trabalho

- Prefiro sistema instrumentado e com memória a demo bonita que não roda depois
- Gosto de resolver o problema de negócio primeiro, escolher a stack depois
- Hackathons e comunidades open-source de IA são onde eu testo ideia rápido
