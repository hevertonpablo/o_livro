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

### Decidido
- **DEC-037:** **Mulher da Foto = rastro visual da Primeira Guardiã** (unificação canônica interna). As duas fichas — `personagens/apoio/mulher-da-foto.md` e `personagens/sementes/primeira-guardia.md` — referem-se à mesma pessoa. **A Fase 1 nunca confirma.** Hipóteses do leitor (viajante do tempo, semelhança genética, lenda, figura mítica) seguem convivendo. Possível livro próprio na Fase 2.

### Adicionado
- [`books/personagens/apoio/bia.md`](books/personagens/apoio/bia.md) — nova personagem de apoio cruzado: **Beatriz "Bia"**, psicóloga clínica / terapeuta sexual (38–42 anos). Apoio em três núcleos: Clara (L4), Nina (L7), Sofia (L8). Trajetória interna: criação religiosa repressora rompida.

### Alterado
- [`DECISIONS.md`](DECISIONS.md) — adicionada DEC-037.
- [`books/personagens/apoio/mulher-da-foto.md`](books/personagens/apoio/mulher-da-foto.md) — reescrita com camadas externa/interna, plantio canônico por livro, sinais visuais recorrentes, hipóteses do leitor, regra absoluta de revelação.
- [`books/personagens/sementes/primeira-guardia.md`](books/personagens/sementes/primeira-guardia.md) — adicionada função 5 (rastro visual em fotografias) e seção "Como aparece" agora dividida em dois rastros: letra (DEC-021) + imagem (DEC-037).
- [`books/biblia-do-antigo.md`](books/biblia-do-antigo.md) §7.2 — entrada da Mulher da Foto unificada com Primeira Guardiã; §14 e §20 atualizados.
- [`books/biblia-pistas-codigos-charadas.md`](books/biblia-pistas-codigos-charadas.md) §9.1 nova entrada de pista verdadeira; §9.2 red herring "Pessoa misteriosa em foto = Elias jovem" reformulado; §16 atualizado.
- [`books/biblia-de-elias.md`](books/biblia-de-elias.md) §20 — pendência da Mulher da Foto resolvida com DEC-037.
- [`books/biblia-do-personagem-oculto.md`](books/biblia-do-personagem-oculto.md) §16.6 nova — A Mulher da Foto.
- [`books/biblia-continuidade-personagens.md`](books/biblia-continuidade-personagens.md) §4.3 (entrada da Mulher da Foto) e seção camada interna canônica (§12).
- [`books/biblia-continuidade-relacoes.md`](books/biblia-continuidade-relacoes.md) §1.2 — novos vínculos (Mulher da Foto × Nina/Elias/Matusalém; Primeira Guardiã × Elias/Matusalém).
- [`books/objetos/circulantes/foto-antiga.md`](books/objetos/circulantes/foto-antiga.md) §2 (descrição visual canônica), §6 (conexões), §9 (decisões resolvidas).
- [`books/personagens/protagonistas/nina.md`](books/personagens/protagonistas/nina.md) — entrada da Mulher da Foto atualizada.

### Adicionado (continuação — Bia)
- [`books/personagens/apoio/bia.md`](books/personagens/apoio/bia.md) (item criado anteriormente nesta sessão).

### Alterado (continuação — Bia)
- `books/biblia-continuidade-personagens.md` §4.3 + §5 (Bia em personagens-ponte).
- `books/biblia-continuidade-relacoes.md` §1.2 + §12.
- `books/personagens/protagonistas/clara.md`, `nina.md`, `sofia.md` — Bia adicionada ao núcleo de apoio.
- `books/personagens/apoio/README.md` — Bia em Clara + tabela de personagens-ponte.

### Pendente
- Criar `livros/livro-01-lara/` com OUTLINE, ARCOS, MAPA-PISTAS, MAPA-ILUSTRACOES, STATUS, changelog.
- Criar `livros/livro-01-lara/` com OUTLINE, ARCOS, MAPA-PISTAS, MAPA-ILUSTRACOES, STATUS.
- Definir `skills/` e `prompts/` (estrutura sugerida pelo PRD agentic).

---

## 2026-05-09 — Rodada 2 de decisões processada

### Decidido — 6 decisões aprovadas (V2)

Decisões aprovadas pelo autor em [`DECISOES-PARA-RESPONDER-V2.md`](DECISOES-PARA-RESPONDER-V2.md) e propagadas:

- **DEC-017:** Tipo dominante de vida secreta de Elias — **Sacrifício + Culpa + Missão + Espiritual** (4 camadas com hierarquia). Subcamada possível: Identidade (não dominante). Antigo = elo importante, **não a origem**.
- **DEC-020:** Profissão de Clara — **psicóloga clínica com modelo híbrido** (consultório próprio + vínculo eventual com hospital + projeto social com adolescentes em vulnerabilidade).
- **DEC-021:** Três letras manuscritas — **A = B = C com escala temporal**. Mesma origem caligráfica em fases diferentes da vida. Autora interna canônica = **Primeira Guardiã** (figura anterior a Elias e a Matusalém). Não confirmar na Fase 1.
- **DEC-022:** Promessa antiga — **promessa coletiva herdada por Elias e Matusalém através da Primeira Guardiã**. Frase canônica: *"Que o que estiver perdido ainda encontre quem o chame; e que nenhuma vida ferida atravesse a noite sem uma palavra deixada no caminho."* Revelação parcial em L9 + camadas em L10 + sobras para Fase 2.
- **DEC-035:** Cidade da série — **NÃO há metrô** (proibido na Fase 1). Ratifica recomendação canônica das bíblias de transporte e lugares.
- **DEC-036:** Estação canônica — **rodoviária**. Ratifica recomendação canônica. Cena âncora: Nina × Noemi às 3h16 da manhã.

### Adicionado
- [`books/personagens/sementes/primeira-guardia.md`](books/personagens/sementes/primeira-guardia.md) — ficha da **Primeira Guardiã** (entidade interna canônica anterior a Elias e a Matusalém; nunca confirmada na Fase 1; origem da letra das três fontes manuscritas e da promessa antiga).
- [`books/biblia-de-elias.md`](books/biblia-de-elias.md) §13.5 — A promessa antiga (DEC-022) com plantio dos fragmentos por livro.
- [`books/biblia-do-antigo.md`](books/biblia-do-antigo.md) §17 — Relação com a promessa antiga (DEC-022) + §17.2.1 frase canônica + §17.5 letra das margens (DEC-021).
- [`books/biblia-do-personagem-oculto.md`](books/biblia-do-personagem-oculto.md) §16.5 — A letra do caderno (DEC-021).

### Alterado
- [`DECISIONS.md`](DECISIONS.md) — DEC-017, DEC-020, DEC-021, DEC-022, DEC-035, DEC-036 movidas de `pendente` para `aprovado`. Todas as DECs registradas estão agora aprovadas.
- [`books/personagens/protagonistas/elias.md`](books/personagens/protagonistas/elias.md) — DEC-017 (vida secreta com 4 camadas) + DEC-021 (reconhecimento da letra sem ser autor).
- [`books/personagens/protagonistas/clara.md`](books/personagens/protagonistas/clara.md) — DEC-020 (psicóloga clínica + 3 cenários narrativos canônicos).
- [`books/biblia-de-elias.md`](books/biblia-de-elias.md) §12 — DEC-017 fixada como canon; §20 status atualizado.
- [`books/biblia-do-personagem-oculto.md`](books/biblia-do-personagem-oculto.md) §16, §17, §22 — DEC-021, DEC-022, DEC-031.
- [`books/biblia-do-antigo.md`](books/biblia-do-antigo.md) §20 — DEC-021, DEC-022 marcadas resolvidas.
- [`books/biblia-continuidade-personagens.md`](books/biblia-continuidade-personagens.md) — Clara (DEC-020), Elias (DEC-017, DEC-022), §12 status, nova seção sobre Primeira Guardiã.
- [`books/biblia-continuidade-transporte.md`](books/biblia-continuidade-transporte.md) §15 — DEC-035, DEC-036 marcadas resolvidas.
- [`books/biblia-continuidade-cenarios.md`](books/biblia-continuidade-cenarios.md) §9 — DEC-035/036 resolvidas.
- [`books/biblia-continuidade-lugares.md`](books/biblia-continuidade-lugares.md) §12 — DEC-035/036 resolvidas.
- [`books/objetos/circulantes/carta-antiga.md`](books/objetos/circulantes/carta-antiga.md) — DEC-021 (letra) + DEC-022 (frase canônica) + esclarecimento de autoria.
- [`books/objetos/simbolicos/caderno-do-oculto.md`](books/objetos/simbolicos/caderno-do-oculto.md) — DEC-021 + cena canônica em L10.
- [`books/objetos/simbolicos/o-antigo.md`](books/objetos/simbolicos/o-antigo.md) — atributo Margens com autora canônica.
- [`DECISOES-PARA-RESPONDER-V2.md`](DECISOES-PARA-RESPONDER-V2.md) — marcado como `processado em 2026-05-09`.

### Estado das decisões após esta rodada
- **Aprovadas:** DEC-001 a DEC-036 (todas as 36 decisões registradas).
- **Pendentes:** nenhuma DEC numerada está em aberto. (Decisões secundárias dentro de cada bíblia continuam pendentes — ver TASKS.md.)

---

## 2026-05-09 — Rodada 1 de decisões processada

### Decidido — 13 decisões processadas

Decisões aprovadas pelo autor em [`DECISOES-PARA-RESPONDER.md`](DECISOES-PARA-RESPONDER.md) e propagadas para todas as bíblias afetadas:

- **DEC-018:** Talento canônico de Lara — **restauração e encadernação artesanal** (*"vê com os dedos"*).
- **DEC-019:** Profissão canônica de Rafael — **advogado empresarial** (mentira interna: *"a verdade é aquilo que eu consigo sustentar sem ser desmentido"*).
- **DEC-023:** Casaco do Personagem Oculto — **cinza-chumbo gasto** (variações de percepção permitidas; nunca preto absoluto, marrom vivo ou cor marcante).
- **DEC-024:** Marca canônica do Antigo — **três pontos discretos** em triângulo no canto inferior direito da capa; Lara os sente com os dedos antes de ver.
- **DEC-025:** Cidade-base — **não nomeada** (universalidade controlada confirmada). Tipologia urbana fica registrada em [`books/biblia-continuidade-transporte.md`](books/biblia-continuidade-transporte.md).
- **DEC-026:** Nome interno do Personagem Oculto — **Matusalém** (jamais aparece na obra publicada).
- **DEC-027:** Frase-âncora canônica de variação — *"O que está ___ ainda pode ser chamado."* — confirmada com palavra-pista por livro.
- **DEC-028:** Acrósticos por livro — **L1 = RECOMECO** (capítulos 1–8), demais livros com sugestões internas.
- **DEC-029:** Forma do número 316 em L1 — **mesa 3 + cadeira 16**, **3h16**, **banco 16**. Apartamento, página e placa proibidos no L1.
- **DEC-030:** Cena Lara × Miguel no parque — **18h**, garoa fina, possível sino de angelus ao longe.
- **DEC-031:** Identidade interna do Oculto — **homem comum usado por Deus + guardião indireto do Antigo + ligação antiga com Elias**. Obra nunca confirma; ambiguidade permanece.
- **DEC-032:** Janela cronológica da Fase 1 — **mista** (presente curto Y0–Y+2 + flashbacks profundos por personagem; sem progressão linear livro a livro).
- **DEC-033:** Camadas secundárias do propósito maior — **familiar + missão**, sustentando o núcleo espiritual de DEC-012.
- **DEC-034:** Nova bíblia criada — [`books/biblia-continuidade-transporte.md`](books/biblia-continuidade-transporte.md) — define a "cidade da série" (ônibus 316, app de mobilidade genérico, táxi, bike, moto, estação) já que DEC-025 proíbe nome real.

### Adicionado
- [`books/biblia-continuidade-transporte.md`](books/biblia-continuidade-transporte.md) — Bíblia de Transporte com 15 seções.
- [`books/biblia-continuidade.md`](books/biblia-continuidade.md) §1.0 — janela cronológica oficial (DEC-032) e §14.2 hierarquia de fontes.
- [`books/biblia-pistas-codigos-charadas.md`](books/biblia-pistas-codigos-charadas.md) §2.1.1 — formas oficiais do 316 em L1; §4.2 — tabela de acrósticos com exemplo L1.
- [`books/biblia-do-antigo.md`](books/biblia-do-antigo.md) §1.3 — marca dos três pontos com tabela de leituras múltiplas.
- [`books/biblia-do-personagem-oculto.md`](books/biblia-do-personagem-oculto.md) — identidade interna canônica (Matusalém + guardião + amigo de Elias).
- [`books/biblia-editorial-visual.md`](books/biblia-editorial-visual.md) §7.5 — acrósticos canônicos por livro (DEC-028).

### Alterado
- [`DECISIONS.md`](DECISIONS.md) — 13 decisões movidas de `pendente` para `aprovado`. DEC-035 e DEC-036 mantêm-se como pendentes com recomendação interna.
- [`books/biblia-continuidade-personagens.md`](books/biblia-continuidade-personagens.md) — Lara (DEC-018), Rafael (DEC-019), Personagem Oculto (DEC-023, DEC-026, DEC-031).
- [`books/biblia-continuidade-horarios.md`](books/biblia-continuidade-horarios.md) — cena Lara × Miguel com 18h e garoa fina (DEC-030); §10 atualizada.
- [`books/biblia-continuidade-cenarios.md`](books/biblia-continuidade-cenarios.md) §9 — DEC-019, DEC-025, DEC-035, DEC-036.
- [`books/biblia-continuidade-lugares.md`](books/biblia-continuidade-lugares.md) §12 — DEC-025, DEC-035, DEC-036.
- [`books/biblia-continuidade-clima.md`](books/biblia-continuidade-clima.md) §11 — DEC-025, DEC-030.
- [`books/biblia-continuidade-objetos.md`](books/biblia-continuidade-objetos.md) §11 — DEC-018, DEC-023, DEC-024, DEC-029.
- [`books/personagens/protagonistas/lara.md`](books/personagens/protagonistas/lara.md) — talento (DEC-018) e percepção dos três pontos (DEC-024).
- [`books/personagens/protagonistas/rafael.md`](books/personagens/protagonistas/rafael.md) — profissão (DEC-019) + mentira interna.
- [`books/personagens/recorrentes/personagem-oculto.md`](books/personagens/recorrentes/personagem-oculto.md) — Matusalém + casaco cinza-chumbo + identidade interna.
- [`books/objetos/simbolicos/o-antigo.md`](books/objetos/simbolicos/o-antigo.md) — três pontos (DEC-024).
- [`books/objetos/simbolicos/casaco-do-oculto.md`](books/objetos/simbolicos/casaco-do-oculto.md) — cinza-chumbo (DEC-023).
- [`books/objetos/simbolicos/caderno-do-oculto.md`](books/objetos/simbolicos/caderno-do-oculto.md) — esclarecimento DEC-021 ainda pendente.
- [`DECISOES-PARA-RESPONDER.md`](DECISOES-PARA-RESPONDER.md) — marcado como `processado em 2026-05-09`.

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
