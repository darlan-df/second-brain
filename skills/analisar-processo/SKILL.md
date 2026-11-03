---
name: analisar-processo
description: Analisar criticamente um processo de negócio, distinguindo evidências, hipóteses de causa, riscos e oportunidades de melhoria.
---

# Analisar processo

> Estado: rascunho não validado. Usar como especificação inicial de comportamento.

## Quando usar

Quando houver uma descrição de processo e o objetivo for identificar problemas, variações, riscos, desperdícios e oportunidades de melhoria.

## Entradas mínimas

- Objetivo e resultado esperado do processo.
- Início, fim, principais etapas e responsáveis, mesmo que preliminares.
- Problema ou questão a investigar.
- Indicadores, ocorrências ou evidências disponíveis; registrar ausência deles.

## Procedimento

1. Reformular o objetivo e o limite do processo sem inferir atividades não informadas.
2. Identificar entradas, saídas, decisões, interfaces e atores conhecidos.
3. Distinguir fatos observados de hipóteses e lacunas.
4. Identificar potenciais gargalos, falhas, redundâncias, desperdícios e riscos.
5. Relacionar cada hipótese à evidência disponível e indicar como testá-la.
6. Recomendar intervenções proporcionais ao problema; incluir riscos e impactos.
7. Definir sugestões de indicadores para verificar se a intervenção funcionou.

## Saída

- Contexto e objetivo; limites da análise; mapa descritivo conhecido.
- Constatações comprovadas; hipóteses pendentes; lacunas de informação.
- Oportunidades priorizadas com justificativa, impacto esperado e validação proposta.

## Restrições

Não afirmar causa raiz sem evidência. Não inventar indicadores, frequências, dados nem procedimentos obrigatórios. Explicitar incertezas.

## Conhecimentos relacionados

- [Gestão por processos](../../conhecimentos/gestao-processos/README.md)
- [Dados e decisão](../../conhecimentos/dados-e-decisao/README.md)
- [Negócios e estratégia](../../conhecimentos/negocios-e-estrategia/README.md)
- [Experiência do cliente](../../conhecimentos/experiencia-cliente/README.md)

## Validação

Registrar execução de cenários em [`testes/cenarios/`](../../testes/cenarios/README.md) e evidências em [`testes/resultados/`](../../testes/resultados/README.md).
