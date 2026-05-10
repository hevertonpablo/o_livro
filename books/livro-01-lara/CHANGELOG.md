# Changelog — Livro 1: Lara

> Histórico local de alterações no livro. Para alterações canônicas que afetam toda a série, ver também `../../CHANGELOG.md` da raiz.

---

## 2026-05-09

### Adicionado — arquitetura inicial completa

Pelo Agente de Planejamento ([`../../AGENT-ESCRITA-LIVROS.md`](../../AGENT-ESCRITA-LIVROS.md)), seguindo a sequência §10.1 do agente:

- [`STATUS.md`](STATUS.md) — estado inicial do livro (planejamento — em consolidação).
- [`ARCOS.md`](ARCOS.md) — arco emocional macro de Lara (12 estágios) + 7 arcos secundários (Miguel, Personagem Oculto, Mel, Dona Cida, Beto, Jéssica, fragmentos) + conexões entre arcos.
- [`MAPA-PISTAS.md`](MAPA-PISTAS.md) — controle operacional de todas as pistas: 9 categorias (Antigo, 316, Elias, Personagem Oculto, promessa antiga, letra das três fontes, Mulher da Foto, charada central linha 1, frase-âncora, acróstico) + red herrings + pistas de releitura + 14 decisões pendentes.
- [`MAPA-ILUSTRACOES.md`](MAPA-ILUSTRACOES.md) — sistema visual: 17 imagens planejadas (1 capa + 4 aberturas de parte + 8 símbolos + 4 cenas marcantes), distribuição por capítulo justificada, template de prompt, regras absolutas.
- [`CAPITULOS.md`](CAPITULOS.md) — tabela operacional dos 24 capítulos com status, função (DEC-014), POV, cenário, horário/clima, imagem associada, observações + bloqueios atuais.
- [`capitulos/capitulo-01.md`](capitulos/capitulo-01.md) a [`capitulos/capitulo-24.md`](capitulos/) — 24 placeholders criados com cabeçalho de comentário (função, cenário, horário/clima, pistas obrigatórias, bloqueios) prontos para o Agente de Escrita preencher.

### Decisões canônicas honradas

DEC-001, DEC-002, DEC-003, DEC-004, DEC-006, DEC-008, DEC-009, DEC-010, DEC-011, DEC-013, DEC-014, DEC-015, DEC-018, DEC-021, DEC-022, DEC-023, DEC-024, DEC-025, DEC-026, DEC-027, DEC-028, DEC-029, DEC-030, DEC-031, DEC-032, DEC-037.

### Pendências em aberto

10 pendências registradas em `MAPA-PISTAS.md` §14 + `OUTLINE.md` §9. Bloqueadores diretos da escrita:

1. **Frase exata de Miguel para Lara no Cap 13** (cena travada — afeta L2). **Crítica.**
2. **Segunda fala do Personagem Oculto a Lara no Cap 17.**
3. **Quem entrega o Antigo a Lara no Cap 7.**
4. **Conteúdo exato da inscrição na árvore antiga no Cap 4.**
5. **Epígrafe do livro.**
6. **Como referenciar a tragédia familiar de Lara nos Caps 5 e 22.**
7. **Detalhe visual do Cap 24** (folha caída, pétala, casaco dobrado).

### Capítulos com bloqueio direto

Cap 4, Cap 7, Cap 13, Cap 17, Cap 24 — não podem entrar em rascunho até resolução das pendências correspondentes.

### Arquivos não modificados nesta sessão

- [`OUTLINE.md`](OUTLINE.md) — já estava completo em sessão anterior (nível macro completo, 24 capítulos, 4 partes, acróstico RECOMECO, ~427 linhas). **Mantido.**

### Próximos passos recomendados

1. **Responder [`PENDENCIAS-PARA-RESPONDER.md`](PENDENCIAS-PARA-RESPONDER.md)** — questionário consolidado com as 8 pendências (3 críticas + 3 importantes + 2 secundárias).
2. Atualizar OUTLINE.md adicionando coluna "Imagem associada" em cada entrada de capítulo (referência ao MAPA-ILUSTRACOES).
3. Gerar prompts completos para os 17 itens do MAPA-ILUSTRACOES (Etapa 2 da produção visual).
4. Após resolução das pendências, **invocar o Agente de Escrita** ([`AGENT-ESCRITA-CAPITULOS.md`](../../AGENT-ESCRITA-CAPITULOS.md)) para o Capítulo 1.

---

## 2026-05-09 (segunda atualização)

### Adicionado
- [`PENDENCIAS-PARA-RESPONDER.md`](PENDENCIAS-PARA-RESPONDER.md) — questionário consolidado dos 8 bloqueios do livro:
  - **🔴 Críticas (3):** frase de Miguel no Cap 13 (DEC-038 candidata), segunda fala do Oculto no Cap 17, quem entrega o Antigo no Cap 7.
  - **🟡 Importantes (3):** inscrição na árvore antiga (Cap 4), detalhe visual final (Cap 24), referência à tragédia familiar (Caps 5/22).
  - **🟢 Secundárias (2):** profissão atual de Lara, epígrafe do livro.

### Alterado
- `STATUS.md` — bloqueios consolidados apontando para `PENDENCIAS-PARA-RESPONDER.md`; próximas ações atualizadas.

### Convenção registrada
A criação deste arquivo segue a convenção registrada no Agente de Planejamento `AGENT-ESCRITA-LIVROS.md` §14.2: **questionários de pendências de cada livro vivem dentro do path do livro**, não na raiz do projeto.

---

## 2026-05-09 (terceira atualização) — Pendências processadas

### Decidido
Todas as 8 pendências do livro foram respondidas pelo autor e propagadas:

| # | Pendência | Resolução |
|--:|---|---|
| 1 | Frase de Miguel para Lara no Cap 13 | **DEC-038 ✓** (canon global): *"Tem dia que a gente não está perdido. Só ainda não teve coragem de voltar."* — começa olhando para o lado, termina olhando para ela; tom baixo, sem sermão; camada dupla (sai pra ela, é pra ele). |
| 2 | Segunda fala do Oculto no Cap 17 | (canon do livro): *"O que você tem nas mãos não é o livro. É a ideia de que o livro pode ser cuidado. Cuide assim de você também."* — caderno aberto, parado, sem anotar. |
| 3 | Quem entrega o Antigo no Cap 7 | (canon do livro): cliente anônimo de fala curta, frase: *"Acho que isso te procurou."* |
| 4 | Inscrição na árvore antiga (Cap 4) | **DEC-039 ✓** (canon global): "E" + traço apagado, aparência irregular confundida com desgaste natural. **Não escrever "ELIAS" em qualquer livro da Fase 1.** |
| 5 | Detalhe visual final do Cap 24 | (canon do livro): folha caída sobre o lugar onde ele costumava sentar. |
| 6 | Tragédia familiar de Lara (Caps 5, 22) | (canon do livro): apenas sugerida, nunca detalhada. Flashback Cap 5 = mãos de criança tentando consertar algo + vidro quebrado. |
| 7 | Profissão atual de Lara nos Caps 1–6 | (canon do livro): restauração informal para 1–2 antiquários + corridas com Beto 3x/semana, sem trabalho fixo. |
| 8 | Epígrafe do livro | (canon do livro): *"Algumas histórias começam pela parte que parecia o fim."* — sem atribuição, em letra manuscrita imitando a Primeira Guardiã (DEC-021). |

### Alterado
- [`OUTLINE.md`](OUTLINE.md) §1.1 (DECs novas honradas) e §9 (todas as pendências marcadas como resolvidas).
- [`ARCOS.md`](ARCOS.md) §1.2 (ferida central com elemento concreto do flashback), §1.9 (ponto médio com frase canônica de Miguel), §2.1 (Miguel — frase fixa).
- [`MAPA-PISTAS.md`](MAPA-PISTAS.md) §1 (Cap 7 entregador + frase), §3.1 (Cap 4 inscrição DEC-039), §4.2 (segunda fala canônica do Oculto), §11 (red herring atualizado), §13.1 (epígrafe), §14 (todas as pendências resolvidas).
- [`CAPITULOS.md`](CAPITULOS.md) — bloqueios eliminados; capítulos 4, 7, 13, 17, 24 destravados.
- [`STATUS.md`](STATUS.md) — estado atual atualizado para "concluído / pronto para escrita".
- [`PENDENCIAS-PARA-RESPONDER.md`](PENDENCIAS-PARA-RESPONDER.md) — marcado como `processado em 2026-05-09`.
- Placeholders dos capítulos afetados: **Cap 1, 2, 4, 5, 7, 13, 17, 22, 24** atualizados com os novos canon do livro e referências às DECs novas.

### Decisões canônicas globais criadas
- **DEC-038** — Frase canônica de Miguel para Lara no Cap 13 (cena travada L1/L2).
- **DEC-039** — Inscrição na árvore antiga ("E" + traço apagado, eco em L9).

Ambas registradas em `../../DECISIONS.md`.

### Status final do livro
**Planejamento concluído. L1 destravado para escrita dos 24 capítulos.**

### Próximo passo
Invocar [`AGENT-ESCRITA-CAPITULOS.md`](../../AGENT-ESCRITA-CAPITULOS.md) para escrever o **Capítulo 1 — *Rua Sem Volta***.
