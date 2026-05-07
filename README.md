# Histórias que se Cruzam

> Série de **10 livros independentes e interligados** (Fase 1).
> Cada volume narra a vida de um personagem; em determinados capítulos, as histórias se cruzam e, juntas, revelam um propósito maior.

**Status:** Fase 1 em **planejamento avançado**. Documentação completa, primeiro livro pronto para entrar em outline.

---

## Para humanos: como navegar

1. **Entendendo o projeto** — leia [`CONTEXT_BRIEF.md`](CONTEXT_BRIEF.md) (resumo de 5 minutos).
2. **Direção literária** — leia [`docs/prd-direcao-literaria.md`](docs/prd-direcao-literaria.md).
3. **Estado atual** — confira [`PROJECT_STATUS.md`](PROJECT_STATUS.md).
4. **Decisões canônicas** — veja [`DECISIONS.md`](DECISIONS.md).
5. **O que fazer agora** — abra [`TASKS.md`](TASKS.md).

## Para agents de IA: leia primeiro

1. [`AGENTS.md`](AGENTS.md) — comportamento obrigatório do agente.
2. [`RULES.md`](RULES.md) — leis invioláveis da série.
3. [`CONTEXT_BRIEF.md`](CONTEXT_BRIEF.md) — contexto resumido.
4. [`books/biblia-continuidade.md`](books/biblia-continuidade.md) — hub de todas as bíblias.

---

## Estrutura do repositório

```
book/
├── README.md                       este arquivo
├── AGENTS.md                       como agentes de IA devem se comportar
├── RULES.md                        leis invioláveis da série
├── CONTEXT_BRIEF.md                resumo curto do universo
├── PROJECT_STATUS.md               estado atual do projeto
├── DECISIONS.md                    decisões canônicas (ADR-estilo)
├── CHANGELOG.md                    histórico global de alterações
├── TASKS.md                        tarefas pendentes
├── SESSION_LOG.md                  log de sessões de IA
│
├── docs/                           PRDs e documentação literária
│   ├── escopo.md                       brainstorm de origem
│   ├── prd-literario.md                consolidação anterior
│   └── prd-direcao-literaria.md        direção oficial (limpa)
│
└── books/                          BÍBLIAS técnicas + fichas
    ├── biblia-continuidade.md          ★ HUB do sistema de bíblias
    ├── biblia-continuidade-personagens.md
    ├── biblia-continuidade-relacoes.md
    ├── biblia-continuidade-cenarios.md
    ├── biblia-continuidade-clima.md
    ├── biblia-continuidade-lugares.md
    ├── biblia-continuidade-objetos.md
    ├── biblia-continuidade-horarios.md
    ├── biblia-do-antigo.md
    ├── biblia-do-personagem-oculto.md
    ├── biblia-de-elias.md
    ├── biblia-pistas-codigos-charadas.md
    ├── biblia-editorial-visual.md
    │
    ├── personagens/                    fichas individuais (46 arquivos)
    ├── cenarios/                       lugares-personagem (13)
    ├── clima/                          estações + estados (9)
    ├── lugares/                        tipos de lugar (12)
    ├── objetos/                        objetos por tier (17)
    └── horarios/                       períodos do dia (9)
```

> **Observação:** as bíblias ficam em `books/` (decisão histórica). Em recomendações externas, a pasta às vezes é chamada de `biblias/` — é a mesma coisa. **A pasta canônica é `books/`.**

## Próximos passos

Estrutura completa de planejamento. Próximo grande marco: **iniciar o Outline do Livro 1 (Lara)**. Ver [`TASKS.md`](TASKS.md) para a fila de prioridades.

---

*Para qualquer dúvida sobre o universo: comece pelo `CONTEXT_BRIEF.md`. Para qualquer ação no projeto: comece pelo `AGENTS.md`.*
