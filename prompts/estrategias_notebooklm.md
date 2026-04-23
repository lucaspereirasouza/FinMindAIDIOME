# Estratégias de Prompt para NotebookLM

Este documento contém os prompts sugeridos para interagir com as fontes carregadas no NotebookLM para este projeto.

## Objetivo
Extrair informações estruturadas, definições claras e guias passo a passo sobre educação financeira.

---

## Prompt 1: Síntese de Reserva de Emergência
**Contexto:** Use este prompt após carregar o arquivo `reserva_emergencia.md`.
**Prompt:**
> "Com base no material do Banco Central, crie um guia passo a passo para alguém que nunca poupou. O guia deve incluir: 
> 1. Como calcular o valor alvo da reserva.
> 2. Três dicas práticas para 'pagar-se primeiro'.
> 3. Uma tabela comparativa simples entre Tesouro Selic e CDB de Liquidez Diária para este fim."

## Prompt 2: Desmistificando o Tesouro Direto
**Contexto:** Use este prompt após carregar o arquivo `tesouro_direto.md`.
**Prompt:**
> "Explique o Tesouro Direto para uma criança de 10 anos. Use uma analogia de 'emprestar um brinquedo' para explicar como o governo usa o dinheiro e por que ele paga juros de volta. Destaque por que é seguro."

## Prompt 3: Cruzamento de Informações
**Contexto:** Use este prompt com todas as fontes carregadas.
**Prompt:**
> "Identifique os pontos em comum entre as recomendações do Banco Central e do Tesouro Nacional sobre segurança e liquidez. Por que o Tesouro Selic é frequentemente citado como a melhor opção para a reserva de emergência?"

## Prompt 4: Glossário Automático
**Prompt:**
> "Liste todos os termos técnicos financeiros mencionados nos textos (ex: Liquidez, Selic, IPCA, Risco Soberano) e forneça uma definição curta e simplificada para cada um, focando em quem está começando."
