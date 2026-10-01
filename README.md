# 7 Days of Code — IA para Produtividade

Bem-vindo ao repositório de soluções e gabaritos da trilha de IA para Produtividade!

## Sobre o Projeto

Este repositório contém as soluções completas dos 7 dias de desafio, onde construímos um **Assistente Pessoal de Produtividade**: um conjunto de prompts reutilizáveis para triar e-mails, resumir reuniões, priorizar tarefas, criar modelos de texto e analisar planilhas — tudo usando técnicas de Prompt Engineering (contexto, few-shot, chain of thought, delimitadores e restrições) com a IA generativa de sua preferência (ChatGPT, Claude, Gemini...).

## Navegação pelas Soluções (por Branch)

Selecione a branch correspondente no menu superior do GitHub ou clique nos links abaixo para conferir o gabarito e a explicação de cada dia:

| Dia | Branch | Tema |
|-----|--------|------|
| 1 | [`solucao-dia-1`](../../tree/solucao-dia-1) | Perfil de Rotina de Trabalho |
| 2 | [`solucao-dia-2`](../../tree/solucao-dia-2) | Triagem de e-mails e mensagens |
| 3 | [`solucao-dia-3`](../../tree/solucao-dia-3) | Resumos que poupam tempo |
| 4 | [`solucao-dia-4`](../../tree/solucao-dia-4) | Priorização e plano do dia |
| 5 | [`solucao-dia-5`](../../tree/solucao-dia-5) | Modelos reutilizáveis de texto |
| 6 | [`solucao-dia-6`](../../tree/solucao-dia-6) | Análise de planilhas com IA |
| 7 | [`solucao-dia-7`](../../tree/solucao-dia-7) | Assistente Pessoal de Produtividade (projeto final) |

## O que cada Branch Representa

- **`main`** — Esta branch. Contém apenas este README com a navegação do repositório.
- **`solucao-dia-1`** — Perfil de Rotina de Trabalho: exemplo preenchido do bloco de contexto (cargo, tarefas recorrentes, ferramentas, tempo disponível) reaproveitado nos dias seguintes.
- **`solucao-dia-2`** — Prompt de Triagem: taxonomia própria (urgente / importante / acompanhar / arquivar) e exemplo de classificação de e-mails com Few-Shot Prompting.
- **`solucao-dia-3`** — Prompt de Resumo Fixo: formato padronizado para atas de reunião e documentos longos (decisões, responsáveis, pontos em aberto).
- **`solucao-dia-4`** — Prompt de Priorização: avaliação de tarefas por impacto, urgência e tempo (Chain of Thought) e um plano do dia que respeita o tempo disponível.
- **`solucao-dia-5`** — Banco de Modelos: exemplos reais (Few-Shot) dos textos que mais se repetem no trabalho — status report, follow-up, proposta.
- **`solucao-dia-6`** — Prompt de Análise de Planilhas: delimitadores e restrições para extrair insights sem inventar números que não estão nos dados.
- **`solucao-dia-7`** — Assistente Pessoal de Produtividade: o Mega-Prompt final, compondo os seis blocos anteriores em camadas (contexto → regras por tarefa → instrução geral).

## Técnicas de Prompt Engineering utilizadas

- Engenharia de contexto (Perfil de Rotina de Trabalho)
- Few-Shot Prompting
- Chain of Thought
- Delimitadores e restrições (anti-alucinação)
- Composição de prompts em camadas (Mega-Prompt)

## Ferramentas

- ChatGPT, Claude ou Gemini (qualquer IA generativa de sua preferência)
- Markdown
