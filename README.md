# MAC0470 — Pad de Aulas

Diário de atividades da disciplina **MAC0470 — Desenvolvimento de Software Livre** (IME-USP).

**Nome:** Eduardo Cruz Guedes — NUSP 13672752

Cada página em `docs/aulas/` registra brevemente o tutorial seguido na aula, com observações sobre dificuldades encontradas.

## Adicionar nova aula

1. Descubra o `sidebar_position` da última aula em `docs/aulas/` e use o próximo número.
2. Crie o arquivo `docs/aulas/YYYY-MM-DD.md`:

```md
---
sidebar_position: <próximo número>
---

# Aula DD/MM/YYYY

**Tutorial:** [Título do tutorial](URL)

Uma ou duas frases descrevendo o que o tutorial cobre.

## Observações

- Dificuldades encontradas, desvios do tutorial, etc.
```

3. Salve — o sidebar é gerado automaticamente, nenhuma outra configuração é necessária.

## Desenvolvimento local

```bash
npm install
npm start
```
