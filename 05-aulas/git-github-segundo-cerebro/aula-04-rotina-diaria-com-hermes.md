# Aula 04 — Rotina diária com Hermes e segundo cérebro

## Objetivo

Aprender o fluxo básico para usar o segundo cérebro no dia a dia sem virar bagunça.

## Fluxo diário recomendado

```text
capturar → organizar → registrar decisão → revisar → salvar no GitHub
```

## 1. Capturar rápido

Tudo que ainda não tem lugar entra primeiro em:

```text
00-inbox/
```

Exemplo de pedido para o Hermes:

```text
Gênio, registra no segundo cérebro, na inbox, esta ideia: [ideia].
```

## 2. Organizar por trilho

Depois, mover para o trilho certo:

- `01-pessoal/`
- `02-profissional/`

Exemplo:

```text
Gênio, pega as notas da inbox sobre casamento e organiza em 01-pessoal/casamento.
```

## 3. Registrar decisões importantes

Decisões não devem ficar perdidas no meio de conversas.

Toda decisão relevante vai para:

```text
04-decisoes/
```

Exemplo:

```text
Gênio, registra uma decisão explicando por que escolhemos GitHub Pages para o contador do casamento.
```

## 4. Revisar antes de salvar

Antes de commit, sempre revisar:

```bash
git status --short
git diff
```

O Hermes deve resumir as mudanças, não despejar logs enormes.

## 5. Salvar no GitHub

Depois de revisar:

```bash
git add .
git commit -m "Atualiza notas do segundo cerebro"
git push
```

## Modelo de pedido ideal

```text
Gênio, no segundo cérebro, atualiza [pasta/tema] com:
- contexto
- decisões
- próximos passos

Depois me mostra o resumo das mudanças e, se estiver ok, faz commit e push.
```

## Checklist diário de 5 minutos

- [ ] Coloquei ideias soltas na inbox
- [ ] Organizei pelo menos o que era urgente
- [ ] Registrei decisões importantes
- [ ] Revisei mudanças antes do commit
- [ ] Fiz commit/push se houve mudança relevante
