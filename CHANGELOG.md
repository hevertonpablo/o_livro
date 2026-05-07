# CHANGELOG.md

> Histórico global de alterações no projeto. Inspirado em [Keep a Changelog](https://keepachangelog.com/).
>
> Para histórico **por livro**, ver `livros/livro-XX-NOME/changelog.md` (quando houver).
> Para log de sessões de IA, ver [`SESSION_LOG.md`](SESSION_LOG.md).

**Convenções de seção por entrada:**
- **Adicionado** — novos arquivos / conteúdos / regras.
- **Alterado** — mudanças em arquivos existentes.
- **Decidido** — novas decisões canônicas (referenciar `DEC-XXX`).
- **Revertido** — decisões revertidas.
- **Pendente** — pendências abertas (referenciar tarefa em `TASKS.md`).

---

## [Unreleased]

### Pendente
- Resolver decisões críticas para iniciar L1: DEC-017, DEC-018, DEC-019, DEC-020, DEC-023, DEC-024, DEC-025.
- Criar `livros/livro-01-lara/` com OUTLINE, ARCOS, MAPA-PISTAS, MAPA-ILUSTRACOES, STATUS.
- Definir `skills/` e `prompts/` (estrutura sugerida pelo PRD agentic).

---

## 2026-05-07

### Adicionado — estrutura operacional para agents
- [`README.md`](README.md) — entrada do repositório.
- [`AGENTS.md`](AGENTS.md) — comportamento obrigatório de agentes de IA.
- [`RULES.md`](RULES.md) — leis invioláveis da série (organizadas por categoria).
- [`CONTEXT_BRIEF.md`](CONTEXT_BRIEF.md) — resumo curto do universo.
- [`PROJECT_STATUS.md`](PROJECT_STATUS.md) — estado atual do projeto.
- [`DECISIONS.md`](DECISIONS.md) — decisões canônicas no formato ADR.
- [`CHANGELOG.md`](CHANGELOG.md) — este arquivo.
- [`TASKS.md`](TASKS.md) — tarefas pendentes priorizadas.
- [`SESSION_LOG.md`](SESSION_LOG.md) — log de sessões de IA.

### Decidido
- **DEC-016:** Estrutura operacional para agents implementada na raiz, **mantendo `books/` como pasta canônica de bíblias** (não renomear para `biblias/` por causa do volume de cross-references).

### Adicionado — Bíblia Editorial e Visual
- [`books/biblia-editorial-visual.md`](books/biblia-editorial-visual.md) — controla tamanho dos livros, estrutura de capítulos, partes, abertura, boxes, fragmentos visuais, símbolos, ilustrações, identidade visual.

### Decidido
- **DEC-009:** Tamanho médio dos livros: 240 páginas / 24 capítulos / ~65 mil palavras.
- **DEC-013:** Estrutura em 4 partes por livro.
- **DEC-014:** Função obrigatória de cada capítulo.

### Alterado
- [`books/biblia-continuidade.md`](books/biblia-continuidade.md) — atualizado como hub do sistema. Adicionada seção "Sistema de Bíblias — mapa completo", "Hierarquia de fontes em caso de conflito", e referências cruzadas em §3, §4, §5, §6, §7, §8, §9, §10, §11, §12 apontando para bíblias especializadas.
- [`books/biblia-continuidade.md`](books/biblia-continuidade.md) §13 — adicionadas colunas "Capítulos (alvo)" e "Páginas (alvo)" com metas oficiais.
- [`books/biblia-continuidade.md`](books/biblia-continuidade.md) — apêndice ampliado com lista de todas as bíblias e pastas.

### Adicionado — Bíblia de Elias
- [`books/biblia-de-elias.md`](books/biblia-de-elias.md) — mistério humano, com 20 seções (versões contraditórias, quem fala, quem mente sem saber, quem sabe a verdade, pistas por livro, acusações justas vs incompletas, gestos de bondade, tipos de vida secreta, verdade final, reinterpretação após L9).

### Adicionado — Bíblia do Personagem Oculto
- [`books/biblia-do-personagem-oculto.md`](books/biblia-do-personagem-oculto.md) — mistério espiritual, com 22 seções (sinais recorrentes, aparições por livro, falas canônicas, gestos, cheiros, hipóteses, o que pode ser deduzido, o que nunca confirmar).

### Adicionado — Bíblia do Antigo
- [`books/biblia-do-antigo.md`](books/biblia-do-antigo.md) — mistério do objeto-mestre, com 20 seções (formas percebidas, fragmentos, quem tocou/viu/recusou, frases deixadas, charada central, dúvidas geradas, caminho de suspeita, proibições).

### Adicionado — Bíblia de Pistas, Códigos e Charadas
- [`books/biblia-pistas-codigos-charadas.md`](books/biblia-pistas-codigos-charadas.md) — manual do jogo do leitor, com 16 seções (técnicas, 316, charada, acrósticos, últimas palavras, frases com variação, letras iniciais, falsas pistas, dificuldade, linha do tempo de descoberta, recompensas de releitura, pirâmide de decodificação).

### Adicionado — Bíblia de Relações
- [`books/biblia-continuidade-relacoes.md`](books/biblia-continuidade-relacoes.md) — mapa social com 14 seções (quem conhece quem, quem ouviu falar, conflitos, dívidas, versões sobre Elias, quem foi tocado pelo Oculto, toques no Antigo, mentiras, pirâmide do conhecimento).

### Adicionado — Bíblia de Personagens
- [`books/biblia-continuidade-personagens.md`](books/biblia-continuidade-personagens.md) — quadro emocional dos personagens com 12 seções (cinco peças canônicas por protagonista, recorrentes, apoio, ponte, semente, matriz de aparições, arcos por livro, relações cruzadas).

### Adicionado — Bíblia de Horários
- [`books/biblia-continuidade-horarios.md`](books/biblia-continuidade-horarios.md) — controle de períodos do dia.
- [`books/horarios/`](books/horarios/) — 7 fichas de período (madrugada, amanhecer, manhã, meio-dia, tarde, entardecer, noite) + horários canônicos + README.

### Adicionado — Bíblia de Lugares
- [`books/biblia-continuidade-lugares.md`](books/biblia-continuidade-lugares.md) — tipos de lugar com regra de **universalidade controlada** (sem nomes próprios).
- [`books/lugares/`](books/lugares/) — 10 fichas de tipo de lugar + README.

### Decidido
- **DEC-010:** Cidade-base sem nome (universalidade controlada).
- **DEC-011:** Sem marcas reais.

### Adicionado — Bíblia de Objetos
- [`books/biblia-continuidade-objetos.md`](books/biblia-continuidade-objetos.md) — sistema de 5 tiers (simbólicos, circulantes, cenário, pessoais, transitórios).
- [`books/objetos/`](books/objetos/) — fichas por tier (incluindo o-antigo, caderno-do-oculto, casaco-do-oculto, mala-de-noemi, carta-antiga, foto-antiga, banco-do-oculto, mesa-316, etc.) + README.

### Adicionado — Bíblia de Clima
- [`books/biblia-continuidade-clima.md`](books/biblia-continuidade-clima.md) — controle climático.
- [`books/clima/`](books/clima/) — 4 estações + 6 estados climáticos + README.

### Adicionado — Bíblia de Cenários
- [`books/biblia-continuidade-cenarios.md`](books/biblia-continuidade-cenarios.md) — lugares-personagem.
- [`books/cenarios/`](books/cenarios/) — 12 fichas (parque, cafeteria, igreja-pequena, hospital, biblioteca, estudio-musica, transporte, apartamento-lara, escritorio-rafael, casa-helena, loja-instrumentos, estacao) + README.

### Adicionado — Sistema de Personagens
- [`books/personagens/`](books/personagens/) com 4 subpastas:
  - `protagonistas/` — 9 fichas (Lara, Miguel, Rafael, Clara, Helena, Theo, Nina, Sofia, Elias).
  - `recorrentes/` — 3 fichas (Personagem Oculto, Samuel, Jovem Rica).
  - `apoio/` — 28 fichas (núcleo de 12 fixos + secundários).
  - `sementes/` — 1 ficha (Noemi) + READMEs.

### Adicionado — Bíblia Geral
- [`books/biblia-continuidade.md`](books/biblia-continuidade.md) — primeiro hub de continuidade (linha do tempo, idade por livro, presença, cruzamentos, trajetória do Antigo, pistas, falas do Oculto, versões de Elias, charada central, estado dos livros, decisões pendentes).

### Adicionado — PRDs
- [`docs/prd-direcao-literaria.md`](docs/prd-direcao-literaria.md) — direção oficial limpa em 16 seções.
- [`docs/prd-literario.md`](docs/prd-literario.md) — consolidação anterior, mais detalhada.
- [`docs/escopo.md`](docs/escopo.md) — brainstorm de origem com 5.714 linhas.

### Decidido
- **DEC-001:** Fase 1 com 10 livros.
- **DEC-002:** Ordem oficial dos protagonistas (Lara → Convergência).
- **DEC-003:** O Antigo nunca nomeado diretamente.
- **DEC-004:** Identidade do Personagem Oculto nunca confirmada.
- **DEC-005:** Função distinta de Elias × Oculto.
- **DEC-006:** Livro 9 dedicado a Elias.
- **DEC-007:** Charada central em 10 linhas.
- **DEC-008:** Número-âncora 316.
- **DEC-012:** Eixo do propósito maior (espiritual + redenção + legado).
- **DEC-015:** Sistema de bíblias com hierarquia.

---

## Como atualizar este arquivo

Toda alteração relevante (novo arquivo, nova decisão, mudança de canon) entra aqui:

1. Se a alteração é **na sessão corrente**, adicione em `## [Unreleased]` (criar se não existe).
2. Se a sessão fechou (marco significativo), mova `[Unreleased]` para `## YYYY-MM-DD`.
3. Use as seções: **Adicionado**, **Alterado**, **Decidido**, **Revertido**, **Pendente**.
4. **Sempre** referencie IDs (`DEC-XXX`) e arquivos (`[caminho](caminho)`).
5. **Sempre** atualize [`SESSION_LOG.md`](SESSION_LOG.md) na mesma sessão.
