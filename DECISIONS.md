# DECISIONS.md

> **Decisões canônicas do projeto.** Inspirado em ADR (Architecture Decision Records) de software.
> Toda decisão tem ID estável (`DEC-XXX`), conteúdo, justificativa, status e implicações.

**Status possíveis:**
- `aprovado` — vale como canon. Nenhum agent pode contradizer.
- `pendente` — proposta aguardando validação humana. **Nenhum agent pode aplicar.**
- `revertido` — decisão antes aprovada que foi revertida. Mantida como histórico.

**Regra absoluta:** quando um agent precisar tomar uma decisão canônica nova, **registrar como `pendente`** aqui — nunca aplicar sem aprovação.

---

## Índice

| ID | Decisão | Status |
|---|---|---|
| DEC-001 | Estrutura da Fase 1 (10 livros) | aprovado |
| DEC-002 | Ordem oficial dos protagonistas | aprovado |
| DEC-003 | Natureza do Antigo (não-confirmação) | aprovado |
| DEC-004 | Identidade do Personagem Oculto | aprovado |
| DEC-005 | Função distinta de Elias × Oculto | aprovado |
| DEC-006 | Livro 9 dedicado a Elias | aprovado |
| DEC-007 | Charada central em 10 linhas | aprovado |
| DEC-008 | Número-âncora 316 | aprovado |
| DEC-009 | Tamanho médio dos livros | aprovado |
| DEC-010 | Cidade-base sem nome | aprovado |
| DEC-011 | Sem marcas reais | aprovado |
| DEC-012 | Eixo do propósito maior | aprovado (refinado) |
| DEC-013 | Estrutura em 4 partes por livro | aprovado |
| DEC-014 | Função obrigatória de cada capítulo | aprovado |
| DEC-015 | Sistema de bíblias com hierarquia | aprovado |
| DEC-016 | Estrutura operacional para agents | aprovado |
| DEC-017 | Tipo de vida secreta de Elias | **pendente** |
| DEC-018 | Talento principal de Lara | **aprovado** ✓ |
| DEC-019 | Profissão de Rafael | **aprovado** ✓ |
| DEC-020 | Profissão de Clara | **pendente** |
| DEC-021 | Letra das margens = letra da carta = letra do caderno? | **pendente** |
| DEC-022 | Forma exata da promessa antiga | **pendente** |
| DEC-023 | Cor canônica do casaco do Oculto | **aprovado** ✓ |
| DEC-024 | Símbolo / marca da capa do Antigo | **aprovado** ✓ |
| DEC-025 | Cidade-base interna do autor | **aprovado** (sem cidade — ditado pelas bíblias) ✓ |
| DEC-026 | Nome interno do Personagem Oculto | **aprovado** ✓ |
| DEC-027 | Frase-âncora canônica de variação | **aprovado** ✓ |
| DEC-028 | Acróstico do L1 + distribuição por livro | **aprovado** ✓ |
| DEC-029 | Forma do número 316 em L1 | **aprovado** ✓ |
| DEC-030 | Cena Lara × Miguel — horário exato | **aprovado** ✓ |
| DEC-031 | Identidade interna do Personagem Oculto | **aprovado** ✓ |
| DEC-032 | Janela cronológica da Fase 1 | **aprovado** ✓ |
| DEC-033 | Camadas secundárias do propósito maior (familiar + missão) | **aprovado** ✓ |
| DEC-034 | Bíblia de Transporte criada | **aprovado** ✓ |
| DEC-035 | Existe metrô na cidade? | **pendente** (recomendação: não) |
| DEC-036 | Estação canônica = trem ou rodoviária? | **pendente** (recomendação: rodoviária) |

---

## Decisões aprovadas

### DEC-001 — Estrutura da Fase 1
**Conteúdo:** A Fase 1 terá **10 livros independentes e interligados**.
**Status:** `aprovado` — registrada em todas as bíblias.

### DEC-002 — Ordem oficial dos protagonistas
**Conteúdo:** 1. Lara · 2. Miguel · 3. Rafael · 4. Clara · 5. Helena · 6. Theo · 7. Nina · 8. Sofia · 9. Elias · 10. Convergência.
**Status:** `aprovado`.

### DEC-003 — Natureza do Antigo (não-confirmação)
**Conteúdo:** O Antigo **nunca** será nomeado diretamente como Bíblia, Sagrada Escritura, Palavra ou equivalente. Pode sugerir, sem confirmar.
**Status:** `aprovado`.

### DEC-004 — Identidade do Personagem Oculto
**Conteúdo:** Identidade do Personagem Oculto **nunca** será confirmada. As 5 hipóteses convivem.
**Status:** `aprovado`.

### DEC-005 — Função distinta de Elias × Personagem Oculto
**Conteúdo:** Elias gera **conflito, dúvida, julgamento**. Personagem Oculto gera **paz, respeito, gratidão**.
**Status:** `aprovado`.

### DEC-006 — Livro 9 dedicado a Elias
**Conteúdo:** Elias **não pode ganhar livro próprio antes do L9**. Antes, aparece em fragmentos.
**Status:** `aprovado`.

### DEC-007 — Charada central em 10 linhas
**Conteúdo:** Frase poética em 10 linhas, **uma por livro**. **Nunca aparece em bloco.**
**Status:** `aprovado`.

### DEC-008 — Número-âncora 316
**Conteúdo:** O número **316** aparece em muitas formas **sem ser explicado** pelo narrador.
**Status:** `aprovado`.

### DEC-009 — Tamanho médio dos livros
**Conteúdo:** Padrão da série: **240 páginas, 24 capítulos, ~65 mil palavras** por livro. L7, L9, L10 podem ser maiores.
**Status:** `aprovado`.

### DEC-010 — Cidade-base sem nome
**Conteúdo:** Nenhuma cidade, país, estado ou bairro é nomeado na obra. **Universalidade controlada.**
**Status:** `aprovado`.

### DEC-011 — Sem marcas reais
**Conteúdo:** Nenhuma marca real (carro, telefone, café, app, banda, livro). Substituir por descrições genéricas.
**Status:** `aprovado`.

### DEC-012 — Eixo do propósito maior (refinado em 2026-05-07)
**Conteúdo:** **Combinação espiritual + redenção + legado** como **três pilares**, ancorada no Antigo, no Personagem Oculto e em Elias.
- **Pilar 1 — Espiritual:** Deus operando silenciosamente.
- **Pilar 2 — Redenção:** vidas quebradas restauradas por meio de outras vidas.
- **Pilar 3 — Legado:** o Antigo, Elias e os fragmentos deixados no caminho.
**Camadas secundárias** (DEC-033): familiar e missão — não pilares principais.
**Status:** `aprovado`.

### DEC-013 — Estrutura em 4 partes por livro
**Conteúdo:** 4 partes (cap 1–6 / 7–12 / 13–18 / 19–24).
**Status:** `aprovado`.

### DEC-014 — Função obrigatória de cada capítulo
**Conteúdo:** Cada capítulo tem **pelo menos 2 elementos** entre: avanço emocional, conflito, revelação, decisão, consequência, pista, cruzamento, frase marcante, gancho.
**Status:** `aprovado`.

### DEC-015 — Sistema de Bíblias com hierarquia
**Conteúdo:** 13 bíblias técnicas + hub central (agora 14 com a de Transporte). Em conflito, **a especializada vence**.
**Status:** `aprovado`.

### DEC-016 — Estrutura operacional para agents
**Conteúdo:** Raiz com `AGENTS.md`, `RULES.md`, `CONTEXT_BRIEF.md`, `PROJECT_STATUS.md`, `DECISIONS.md`, `CHANGELOG.md`, `TASKS.md`, `SESSION_LOG.md`, `README.md`. Pasta canônica de bíblias permanece `books/`.
**Status:** `aprovado` — implementado em 2026-05-07.

### DEC-018 — Talento principal de Lara ✓ **(NOVO — aprovado em 2026-05-07)**
**Conteúdo:** Talento oficial de Lara é **restauração e encadernação artesanal de objetos antigos**.

Lara sabe recuperar papéis frágeis, cartas, fotografias, capas, cadernos, volumes danificados e pequenos objetos de memória. Seu olhar percebe rasgos, marcas, costuras, manchas, tintas antigas e detalhes que passam despercebidos por outras pessoas.

- **Origem:** o talento nasceu **antes da tragédia da infância**, quando ela ainda acreditava que coisas quebradas podiam ser cuidadas. Após a queda, ela **abandonou** esse dom — mas ele permanece como uma parte preservada de quem ela era.
- **Habilidade secundária:** escrita íntima em cadernos e fragmentos.
- **Passado associado:** dança / vida noturna como **máscara**, não como vocação.
- **Função na trama:** Lara pode ser a **primeira a perceber** que o Antigo não é só velho — tem partes de épocas diferentes, marcas escondidas, foi remendado mais de uma vez, possui fragmentos inseridos depois, tem algo costurado, colado ou oculto.

**Justificativa:** dá a Lara função única na trama maior — ela é a personagem que *vê com os dedos*. Conecta diretamente o arco emocional dela ao Antigo de forma orgânica.

**Implicações:**
- Cena de abertura do L1 pode mostrar Lara com objetos abandonados desse ofício.
- Em L1 ou L2, ela retoma o ofício gradualmente.
- Em L7, a investigação de Nina pode se beneficiar do olhar dela (cruzamento).
- O Antigo passa a ter camada nova: alguém pode **ler suas marcas físicas**, não apenas seu conteúdo.

**Status:** `aprovado`.

### DEC-019 — Profissão de Rafael ✓ **(NOVO — aprovado em 2026-05-07)**
**Conteúdo:** Rafael é **advogado empresarial**, especializado em contratos, crises de reputação e defesa de clientes influentes.

- **Imagem pública:** homem inteligente, elegante, bem-sucedido, confiável.
- **Atuação:** casos discretos, negociações sensíveis, problemas que pessoas ricas/poderosas não querem ver expostos.
- **Mentira interna:** *"A verdade é aquilo que eu consigo sustentar sem ser desmentido."* / *"Ninguém precisa ser inocente. Só precisa parecer limpo."*
- **Conflito central:** um caso antigo, uma decisão profissional ou uma omissão moral começa a voltar à superfície, revelando que sua carreira foi construída não apenas sobre competência, mas também sobre **silêncios convenientes**.
- **Segredo provável:** ajudou a esconder ou suavizar caso antigo — possíveis ligações com família influente, empresa, casa noturna, hospital, instituição religiosa, acidente, mulher vulnerável, denúncia que nunca avançou. Pode tocar indiretamente Lara, Helena, Elias ou Nina.

**Justificativa:** advogado vive no limite entre verdade e versão; culpa e defesa; ética e sucesso; imagem pública e bastidores. Cria **contraste perfeito com Lara**: ela é julgada porque seus erros são visíveis; ele é respeitado porque aprendeu a esconder os dele com palavras bonitas.

**Por que outras opções foram descartadas:**
- Médico — pesa demais com culpa de morte; competiria com Lara e Elias.
- Empresário — genérico demais.
- Pastor — carrega demais o ambiente espiritual da obra; pode dar impressão de ataque.
- Jornalista — combina mais com Nina.
- Político — puxaria para thriller político/social.

**Status:** `aprovado`.

### DEC-023 — Cor canônica do casaco do Oculto ✓ **(NOVO — aprovado em 2026-05-07)**
**Conteúdo:** **Cinza-chumbo gasto.**

- Casaco simples, antigo, discreto.
- Não deve parecer elegante, caro ou chamativo.
- Cor pode ser descrita de forma variável pelos personagens — **cinza escuro, cinza de chuva, carvão gasto, tecido escurecido pelo tempo** — mas **nunca deve virar preto absoluto, marrom vivo ou cor marcante**.

**Função visual:**
- Reforçar discrição.
- Combinar com chuva, madeira, café e papel antigo.
- Permitir reconhecimento em fotos antigas e cenas recorrentes.
- Manter ambiguidade entre presença comum e presença simbólica.

**Regra:** *o casaco é sempre o mesmo, mas a percepção da cor pode variar conforme luz, clima, memória e ponto de vista.*

**Status:** `aprovado`.

### DEC-024 — Símbolo / marca da capa do Antigo ✓ **(NOVO — aprovado em 2026-05-07)**
**Conteúdo:** **Três pontos quase apagados, formando um triângulo imperfeito.**

- A marca aparece na capa, mas está tão desgastada que **alguns personagens não percebem**.
- Outros veem apenas três pequenas depressões, marcas de tinta antiga, furos, queimaduras ou pontos escurecidos no material.
- A disposição lembra um triângulo, mas **nunca é descrita como símbolo religioso explícito**.

**Múltiplas leituras possíveis** (todas convivem sem confirmação):
| Possível leitura | O que sugere |
|---|---|
| Três promessas | Liga ao mistério do 316 |
| Três pessoas originais | Elias, Samuel e outra pessoa |
| Três caminhos | Cada vida escolhendo uma direção |
| Três tempos | Passado, presente, futuro |
| Três marcas de desgaste | Pode parecer apenas dano antigo |
| Três pontos de uma costura | Liga à restauração/encadernação de Lara |
| Três vidas cruzadas | Eco visual do tema da série |

**Regra narrativa:** a marca **nunca deve ser explicada diretamente** nos primeiros livros. Aparece como detalhe visual recorrente, percebido de formas diferentes por personagens diferentes.

**Conexão forte com DEC-018:** Lara (restauração e encadernação) pode ser a **primeira a contar os pontos** com os dedos.

**Status:** `aprovado`.

### DEC-025 — Cidade-base interna do autor ✓ **(NOVO — aprovado em 2026-05-07)**
**Conteúdo:** **Não há cidade-base específica.** A geografia, clima, transporte, lugares e cenários são **construídos pelas próprias bíblias**, não imitam nenhuma cidade real.

Este fortalece a regra DEC-010 (universalidade controlada): a cidade da série é **universal não apenas por não ser nomeada, mas por não ter referente real**.

**Implicações:**
- Quando uma decisão geográfica/climática/urbana surgir, ela é **escolha autoral livre** registrada em bíblia, não decorrência de uma cidade real.
- Foi criada a **Bíblia de Transporte** (DEC-034) para construir o sistema de transporte ficcional.
- Não há reverso possível para "esta é cidade X" — a cidade da série é *uma cidade qualquer construída para a obra*.

**Status:** `aprovado`.

### DEC-026 — Nome interno do Personagem Oculto ✓ **(NOVO — aprovado em 2026-05-07)**
**Conteúdo:** **Matusalém** (nome canônico interno).

- **Nome funcional nos documentos:** "O Observador" (já usado nas bíblias — segue válido).
- **Regra narrativa:** o nome **Matusalém nunca deve aparecer na narrativa publicada da Fase 1**, exceto se futuramente o autor decidir usar como pista extremamente rara, ambígua ou simbólica.

**Como os personagens se referem a ele (descrições, sem nome):**
- *"o homem do casaco cinza"*
- *"o homem do banco"*
- *"o desconhecido"*
- *"o senhor de olhar calmo"*
- *"aquele homem"*
- *"o homem que parecia sempre estar ali"*
- *"o homem que não parecia ter pressa do tempo"*

**Justificativa:** Matusalém é o nome bíblico do homem que viveu mais tempo. Ressoa simbolicamente com a presença atemporal do personagem, sem que a obra precise confirmar nada sobrenatural.

**Status:** `aprovado`.

### DEC-027 — Frase-âncora canônica de variação ✓ **(NOVO — aprovado em 2026-05-07)**
**Conteúdo:** **Confirmada** *"O que está ___ ainda pode ser chamado."*

Variações por livro (palavras-pista):
| L | Variação |
|---|---|
| L1 | perdido |
| L2 | quebrado |
| L3 | escondido |
| L4 | cansado |
| L5 | silenciado |
| L6 | esquecido |
| L7 | esquecido / prestes (a definir) |
| L8 | prestes |
| L9 | escolhido |
| L10 | chamou |

**Status:** `aprovado`.

### DEC-028 — Acróstico do L1 + distribuição por livro ✓ **(NOVO — aprovado em 2026-05-07)**
**Conteúdo:**

**Livro 1 — palavra-acróstico:** **RECOMECO** (RECOMEÇO sem cedilha para fins de acróstico).

- **Aplicação:** primeiras letras dos títulos dos **capítulos 1 a 8** do L1 formam *R-E-C-O-M-E-C-O*.
- **Função:** representar o arco emocional de Lara — queda, vergonha, limite e início de reconstrução.
- **Regra:** o acróstico **não deve ser anunciado, explicado ou destacado**. Funciona como pista invisível para leitores atentos.

**Distribuição sugerida por livro:**
| Livro | Acróstico | Tamanho | Aplicação sugerida |
|---|---|---|---|
| L1 — Lara | **RECOMECO** | 8 letras | Cap 1–8 |
| L2 — Miguel | CAMINHO | 7 letras | Cap 1–7 |
| L3 — Rafael | MASCARA | 7 letras | Cap 1–7 |
| L4 — Clara | CUIDADO | 7 letras | Cap 1–7 |
| L5 — Helena | PERDAO | 6 letras | Cap 1–6 |
| L6 — Theo | RITMO | 5 letras | Cap 1–5 |
| L7 — Nina | VESTIGIO | 8 letras | Cap 1–8 |
| L8 — Sofia | LIMITE | 6 letras | Cap 1–6 |
| L9 — Elias | PROMESSA | 8 letras | Cap 1–8 |
| L10 — Convergência | CONVERGENCIA | 12 letras | Cap 1–12 |

**Status:** `aprovado` (L1 fixado; demais como sugestão a confirmar livro a livro).

### DEC-029 — Forma do número 316 em L1 ✓ **(NOVO — aprovado em 2026-05-07)**
**Conteúdo:** **Aparições oficiais no Livro 1:**

1. **Mesa 3 + cadeira 16** na cafeteria (clara, primeira pista visual).
2. **3h16** em um relógio/celular/despertador de Lara (emocional, liga o número à dor).
3. **Banco 16** no parque (quase invisível, opcional, recompensa de releitura).

**Quantidade:** 2 aparições claras + 1 quase invisível.

**Regras:**
- O número 316 **nunca é explicado** no Livro 1.
- Deve parecer coincidência ou detalhe de cenário.
- **Não usar** apartamento 316, página 316 ou placa "3.16" no L1 — fica óbvio demais.

**Exemplos canônicos:**
> *Lara sentou na mesa 3. A cadeira, marcada com uma pequena plaquinha de metal, trazia o número 16.*
>
> *Quando a tela do celular acendeu, eram 3h16. Lara não sabia se tinha dormido ou apenas desistido de pensar por alguns minutos.*

**Status:** `aprovado`.

### DEC-030 — Cena Lara × Miguel — horário exato ✓ **(NOVO — aprovado em 2026-05-07)**
**Conteúdo:** **18h** (cair da tarde, sob garoa fina).

- **Atmosfera canônica:** garoa fina, luz baixa, início da transição entre dia e noite.
- **Função simbólica:** marca um limiar — Lara ainda está presa ao que foi, mas começa a ser tocada por algo que pode mudar seu caminho.
- **Sino do angelus:** pode tocar ao longe — opção forte de continuidade sonora.

**Regra de continuidade:**
A mesma cena é descrita no L1 (POV Lara) e no L2 (POV Miguel), com horário, clima, cenário e elementos visuais principais **idênticos**.

**Status:** `aprovado`.

### DEC-031 — Identidade interna do Personagem Oculto (Matusalém) ✓ **(NOVO — aprovado em 2026-05-07)**
**Conteúdo:** Para uso interno do autor:

> **Matusalém é um homem comum usado por Deus, que se tornou guardião indireto do Antigo e possui uma ligação antiga com Elias.**

A **narrativa nunca confirma** isso ao leitor. Para os personagens, ele pode parecer sábio, desconhecido bondoso, homem enviado por Deus, anjo disfarçado, alguém que sempre aparece na hora certa.

**Combinação canônica interna:** Homem comum + Guardião indireto do Antigo + Amigo antigo de Elias.

**Hipóteses descartadas como base autoral** (mas ainda permitidas como hipóteses do leitor):
- Anjo disfarçado — risco de tornar a escrita sobrenatural demais.
- Narrador oculto da série — risco literário desnecessário.

**Regra de ambiguidade (canônica):**
> *Mesmo que o autor saiba que Matusalém é um homem comum usado por Deus, a narrativa deve preservar a dúvida. Nenhuma cena deve provar definitivamente que ele é apenas humano. Nenhuma cena deve provar definitivamente que ele é sobrenatural. Ele deve permanecer no limite entre presença humana e sinal espiritual.*

**Como deve soar ao escrever:**
- Não fala como profeta teatral.
- Fala como alguém simples, calmo e antigo.

**Frases-exemplo:**
> *"Às vezes, a gente chega tarde porque queria entender o caminho. Mas tem resposta que só aparece quando a gente para."*
>
> *"Eu não trago ninguém de volta, menina. Só lembro alguns de que ainda podem voltar."*

**Resumo operacional:**
> Para o autor, Matusalém é humano. Para a história, ele permanece mistério. Para os personagens, ele parece resposta.

**Status:** `aprovado`.

### DEC-032 — Janela cronológica da Fase 1 ✓ **(NOVO — aprovado em 2026-05-07)**
**Conteúdo:** **Mista** — presente em janela curta de 1 a 2 anos + flashbacks profundos por personagem.

**A Fase 1 não avança em linha reta livro por livro.** Cada livro pode cobrir períodos sobrepostos, retornos ao passado e cenas simultâneas com outros volumes.

**Camadas cronológicas:**
| Camada | Período |
|---|---|
| Presente principal | Y0 até Y+1 ou Y+2 |
| Flashbacks recentes | Y-1 até Y-5 |
| Flashbacks de formação | infância/adolescência dos protagonistas |
| Passado de Elias | Y-20, Y-30 ou mais |
| Origem do Antigo / promessa | passado mais profundo, revelado aos poucos |

**Distribuição por livro:**
| Livro | Janela principal |
|---|---|
| L1 — Lara | Y0, início da virada |
| L2 — Miguel | Y0, com flashbacks da infância/adolescência |
| L3 — Rafael | Y0, em paralelo a alguns eventos do L1/L2 |
| L4 — Clara | Y0/Y+1 |
| L5 — Helena | Y0/Y+1, com passado familiar forte |
| L6 — Theo | Y0/Y+1 |
| L7 — Nina | Y+1, investigando rastros anteriores |
| L8 — Sofia | Y+1, depois de Lara já ter iniciado mudança |
| L9 — Elias | passado profundo + Y+1 |
| L10 — Convergência | Y+1/Y+2 |

**Justificativa:** janela curta permite cenas compartilhadas, encontros no parque com perspectivas diferentes, o Antigo passando de mão em mão com ritmo, e Convergência parecer real.

**Status:** `aprovado`.

### DEC-033 — Camadas secundárias do propósito maior ✓ **(NOVO — aprovado em 2026-05-07)**
**Conteúdo:** **Familiar** e **Missão** entram como **camadas secundárias** do propósito maior — não como pilares principais.

- **Familiar** — aparece em arcos específicos (Helena, Elias, Lara, Sofia). A série **não depende de uma revelação familiar única** para explicar todas as conexões. Nem todos precisam ser parentes.
- **Missão** — não é o pilar principal, mas pode surgir como **consequência no Livro 10**. Ao compreenderem as conexões, alguns personagens podem escolher agir juntos, proteger alguém, revelar uma verdade, preservar o legado do Antigo ou impedir que uma nova pessoa repita um ciclo de dor.

**Hierarquia oficial do propósito maior:**

| Nível | Elemento | Função |
|---|---|---|
| Pilar 1 | **Espiritual** | Deus operando silenciosamente |
| Pilar 2 | **Redenção** | Vidas quebradas restauradas por meio de outras vidas |
| Pilar 3 | **Legado** | O Antigo, Elias e os fragmentos deixados no caminho |
| Camada secundária | Familiar | Feridas, reconciliações e verdades de família em alguns arcos |
| Camada secundária | Missão | Consequência final no L10 |

**Status:** `aprovado`.

### DEC-034 — Bíblia de Transporte criada ✓ **(NOVO — aprovado em 2026-05-07)**
**Conteúdo:** Criada [`books/biblia-continuidade-transporte.md`](books/biblia-continuidade-transporte.md).

A bíblia constrói o sistema de transporte ficcional da cidade da série (sem cidade real, conforme DEC-025). Define o que existe (ônibus 316, aplicativo genérico, táxi, bicicleta, moto, a pé) e o que ainda precisa ser decidido (DEC-035 metrô, DEC-036 estação).

**Status:** `aprovado` — bíblia criada.

---

## Decisões pendentes

> Propostas aguardando validação humana. **Nenhum agent pode aplicar como verdade.**

### DEC-017 — Tipo de vida secreta de Elias
**Proposta:** Combinação de **Sacrifício + Missão + Espiritual** (recomendação interna).
**Bloqueia:** Plantio em L4 e seguintes; carta antiga (L5).
**Status:** `pendente`.

### DEC-020 — Profissão de Clara
**Alternativas:** Psicóloga · Assistente social · Mentora comunitária · Educadora.
**Bloqueia:** Detalhamento do hospital/projeto social (L4).
**Status:** `pendente`.

### DEC-021 — Letra A = B = C?
**Alternativas:**
- A = B = C (Personagem Oculto = autor das margens = Elias)
- A = B ≠ C (Elias escreveu margens e carta; Oculto separado)
- Três letras diferentes
**Bloqueia:** Cenas de L5 (carta), L7 (investigação visual), L9 (revelação).
**Status:** `pendente`.

### DEC-022 — Forma exata da promessa antiga
**Alternativas:** Promessa de Elias a alguém · Oração antiga geracional · Promessa familiar · Compromisso de proteção.
**Bloqueia:** L5 (carta), L9 (revelação), L10 (cumprimento).
**Status:** `pendente`.

### DEC-035 — Existe metrô na cidade?
**Recomendação interna:** **Não** — mais universal; ônibus 316 ganha protagonismo.
**Bloqueia:** descrições urbanas em vários livros.
**Status:** `pendente`.

### DEC-036 — Estação canônica = trem ou rodoviária?
**Recomendação interna:** **Rodoviária** — mais brasileira, casa com a senhora do terço, com Beto, com a populariedade da obra. A frase de Noemi *"Um dia eu conto minha história"* ganha peso de **estrada longa**.
**Bloqueia:** L7 (cena Nina × Noemi).
**Status:** `pendente`.

---

## Decisões revertidas

*(Nenhuma até o momento.)*

---

## Como propor uma decisão nova

Se você é um agent e identificou uma decisão necessária:

1. **NÃO aplique.** Pare a escrita.
2. **Adicione aqui** com próximo ID disponível e status `pendente`.
3. **Estruture:** Conteúdo / Justificativa / Alternativas / Bloqueia.
4. **Anote em** [`SESSION_LOG.md`](SESSION_LOG.md).
5. **Aguarde** validação humana.
