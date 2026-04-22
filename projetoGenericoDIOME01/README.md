# FinMindAIDIOME — Caderno Temático com IA

## 1. Contexto e Objetivos
Este projeto é um caderno temático digital focado em **Educação Financeira Básica**, desenvolvido com o apoio do **NotebookLM** da Google. 

O objetivo principal é validar como a Inteligência Artificial pode ser utilizada para transformar informações brutas em conhecimento estruturado, facilitando o aprendizado de temas complexos como investimentos, reserva de emergência e juros compostos.

**Objetivos de Estudo:**
- Compreender os pilares da saúde financeira.
- Identificar as melhores estratégias de reserva de emergência.
- Dominar o funcionamento básico de investimentos de renda fixa.

---

## 2. Curadoria de Fontes
As fontes abaixo foram extraídas de órgãos oficiais e servem como base para este caderno:

*   [Reserva de Emergência - BCB](file:///home/lucaspsouza/git/FinMindAIDIOME/projetoGenericoDIOME01/fontes/reserva_emergencia.md) - Orientações sobre segurança financeira.
*   [Tesouro Direto - Portal Oficial](file:///home/lucaspsouza/git/FinMindAIDIOME/projetoGenericoDIOME01/fontes/tesouro_direto.md) - Definição e funcionamento dos títulos públicos.
*   [Cadernos de Educação Financeira (BCB)](https://www.bcb.gov.br/cidadaniafinanceira/educacaofinanceira) - Material técnico de referência.

---

## 3. Engenharia de Prompts e "Cicatrizes"
Nesta seção, documentamos o processo de "conversa" com a IA.

### Perguntas Estratégicas:
1. "Quais são os 3 passos fundamentais para montar uma reserva de emergência segundo as fontes?"
2. "Como o Tesouro Direto democratiza o acesso a investimentos?"
3. [Veja todos os prompts detalhados aqui.](file:///home/lucaspsouza/git/FinMindAIDIOME/projetoGenericoDIOME01/prompts/estrategias_notebooklm.md)

### Troubleshooting (Cicatrizes):
*   **SPA Content:** Páginas oficiais do BCB exigem renderização de JavaScript para extração de texto, dificultando a raspagem simples (resolvido via Browser Agent).
*   **Atualização de Links:** Links diretos de manuais em PDF mudam com frequência; recomenda-se usar as páginas de portal como referência.

---

## 4. Miniguia de Estudo (Entrega Final)
O resultado consolidado deste projeto pode ser encontrado nas pastas:
- [/resumos](file:///home/lucaspsouza/git/projetoGenericoDIOME01/resumos)
- [/glossario](file:///home/lucaspsouza/git/projetoGenericoDIOME01/glossario)
- [/prompts](file:///home/lucaspsouza/git/projetoGenericoDIOME01/prompts)

---

## Estrutura do Repositório
```
/FinMindAIDIOME
│
├── README.md
├── /fontes        # Documentos base (PDF/Texto)
├── /prompts       # Estratégias de perguntas para IA
├── /resumos       # Conteúdo sintetizado
└── /glossario     # Termos técnicos explicados
```
