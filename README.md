# 📬 Dia 2 · Triagem de e-mails

Prompt (exemplo):

```
CONTEXTO: [Perfil do Dia 1]

TAREFA:
Classifique cada e-mail em: URGENTE (hoje) / IMPORTANTE (até 2 dias) /
ACOMPANHAR (só ler) / ARQUIVAR (sem valor).
| Remetente | Categoria | Motivo em até 10 palavras |

E-MAILS:
"""
1. Fornecedor de mídia: campanha pausada, falta aprovar a arte até amanhã.
2. RH: pesquisa de clima organizacional aberta até sexta.
3. Parceiro comercial: remarcar a reunião de terça para quinta?
4. Newsletter: "5 tendências de IA para 2026".
5. Colega de equipe: relatório de março, só para conhecimento.
"""
```

**Saída esperada:**

| Remetente | Categoria |
|---|---|
| Fornecedor de mídia | URGENTE |
| RH | ACOMPANHAR |
| Parceiro comercial | IMPORTANTE |
| Newsletter | ARQUIVAR |
| Colega de equipe | ACOMPANHAR |

Essa tabela é o primeiro bloco do Assistente Pessoal de Produtividade (Dia 7).
