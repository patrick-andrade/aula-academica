# aula-academica

Skill para planejar e produzir aulas universitárias em Economia e Ciências Sociais Aplicadas a partir da bibliografia do curso.

O aplicativo do agente lê esta ficha e segue o ritual: reconstruir o argumento da fonte, explicar o que o estudante precisa para acompanhar sem leitura prévia, apresentar um plano pedagógico e só então gerar os arquivos (slides, Quarto, PPTX).

A skill **não** dispara por contexto. Ter um PDF, um plano de ensino ou slides abertos não basta: é preciso nomeá-la.

Funciona no [padrão aberto Agent Skills](https://agentskills.io/specification) (`SKILL.md`). Serve nos seus cursos e nos de colegas.

Guia: [Skills na Prática](https://patrick-andrade.github.io/guias/skills-na-pratica.html).

## O que ela faz

- Localiza a aula no plano de ensino (público, duração, o que veio antes e o que vem depois).
- Lê a fonte principal e monta a cadeia: problema, premissas, mecanismo, resultado, limites.
- Monta um inventário de conceitos: cada termo, modelo, autor e afirmação empírica com definição, origem e a lâmina em que é explicado.
- Propõe um plano pedagógico para você revisar, com o que entra e o que é cortado.
- Depois da aprovação, produz a apresentação no formato pedido. Cada lâmina abre conforme o seu tipo (a definição num conceito, a pergunta num modelo, o achado numa evidência), e a fonte aparece no slide: autor e ano no texto, linha de fonte em toda figura e tabela.
- Audita como leitor frio: um revisor que só tem os slides renderizados, sem as notas, confere lâmina a lâmina se cada termo foi definido, se as hipóteses vêm antes do resultado e se a evidência traz estudo e magnitude.
- Revisa uma aula existente comparando plano de ensino, fonte e slides.

Ela decide o conteúdo e a ordem. A forma dos bullets fica com a convenção do seu deck ou com a skill [apresentacao-bullets](https://github.com/patrick-andrade/apresentacao-bullets).

Nos slides, os termos ficam em português ("verificação de aprendizagem", não "exit ticket"), e a distribuição do tempo aparece só no plano pedagógico, nunca nas lâminas ou nas notas do apresentador.

A skill guarda o *como*. O chat continua dizendo *qual* aula, *quais* arquivos e *quando* está pronto.

## Instalar

O caminho mais simples para quem está começando é o **Codex**, com a pasta do curso apontada. O mesmo arquivo vale no Claude Code e no Cursor.

**Neste projeto** (recomendado para um curso):

```bash
npx skills add patrick-andrade/aula-academica
```

**Em todos os projetos desta máquina** (se você usa a skill em várias disciplinas):

```bash
npx skills add patrick-andrade/aula-academica --global
```

`npx` vem com o Node.js e baixa o instalador na hora. Sem isso, copie a pasta da skill para:

```text
.agents/skills/aula-academica/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── auditoria.md
    ├── contrato-da-lamina.md
    └── fontes-e-evidencia.md
```

na raiz da pasta do curso. No Claude Code, o equivalente é `.claude/skills/aula-academica/`. No Cursor, `.agents/skills/` também costuma bastar. Inclua `references/` e `agents/openai.yaml`: o `SKILL.md` sozinho não carrega o contrato da lâmina, as regras de fonte e o protocolo de auditoria, nem fecha a invocação implícita no Codex.

Abra um **chat novo** depois de instalar.

## Pedir

Nomeie a skill. Linguagem natural sobre a aula, sem o nome, não a ativa.

**Cursor** e **Claude Code**:

```text
/aula-academica

Objetivo: plano pedagógico da aula de [data], a partir do capítulo
indicado no plano de ensino.
Aguarde minha aprovação antes de gerar os slides.
```

**Codex**:

```text
Use $aula-academica.

Objetivo: plano pedagógico da aula de [data], a partir do capítulo
indicado no plano de ensino.
Aguarde minha aprovação antes de gerar os slides.
```

Também vale pedir em linguagem natural, desde que o nome apareça:

```text
Use a skill aula-academica.

Objetivo: plano pedagógico da aula de [data], a partir do capítulo
indicado no plano de ensino.
Aguarde minha aprovação antes de gerar os slides.
```

A skill trabalha em duas etapas: primeiro o plano; depois os arquivos, quando você aprovar.

## Atualizar

Rode de novo o mesmo comando de instalação (com `--global`, se foi assim que instalou) e abra um chat novo:

```bash
npx skills add patrick-andrade/aula-academica
```

As mudanças de cada versão estão em [Releases](https://github.com/patrick-andrade/aula-academica/releases).

## Licença

[MIT](LICENSE). Você pode usar, copiar e adaptar nos seus cursos; mantenha o aviso de copyright e da licença.
