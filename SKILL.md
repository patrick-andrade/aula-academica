---
name: aula-academica
description: Planeja, produz e revisa aulas universitárias em Economia e Ciências Sociais Aplicadas a partir da bibliografia do curso. Usar somente quando o usuário nomear explicitamente a skill aula-academica.
license: MIT
disable-model-invocation: true
metadata:
  author: Patrick Andrade
  version: "1.3.0"
---

# Aula acadêmica

Transformar a fonte acadêmica em um raciocínio ensinável. Não reduzir um texto a uma coleção de tópicos: reconstruir o problema, as premissas, o mecanismo lógico ou causal, os resultados, as implicações e os limites que permitem ao estudante acompanhar o argumento sem leitura prévia.

O estudante só vê a lâmina. Definição, origem, hipóteses e fonte de que ele precisa para acompanhar o argumento ficam visíveis nela; as notas do apresentador guardam o detalhe que permite conferir.

## Respeitar a hierarquia de autoridade

1. Seguir as instruções explícitas do usuário sobre conteúdo, formato, duração, público e entregáveis.
2. Usar o plano de ensino para delimitar a posição e a função da aula no curso.
3. Tratar a bibliografia indicada como fonte principal do argumento.
4. Usar fontes complementares para explicar pré-requisitos, contexto e controvérsias, sem substituir silenciosamente a fonte principal. Quando a fonte principal enunciar um resultado sem nomear suas hipóteses, sua origem ou sua evidência, buscar isso na obra original e registrar como complemento.
5. Usar o template ou a apresentação de referência como sistema visual, não como autoridade substantiva.

Não inventar leituras, objetivos, dados, posições dos autores ou requisitos ausentes. Explicitar lacunas relevantes e resolver por pesquisa aquelas que forem verificáveis.

## Trabalhar em duas etapas

### Etapa 1 — pesquisar e planejar

Antes de criar os arquivos finais:

1. Inspecionar o plano de ensino, a bibliografia-base, os arquivos de referência e a duração disponível.
2. Ler integralmente o trecho atribuído para a aula; não depender apenas de sumários, buscas ou excertos.
3. Montar o inventário de conceitos (fase 3) e pesquisar os complementos que ele exigir.
4. Apresentar um plano pedagógico para aprovação.
5. Não produzir os arquivos finais até o usuário aprovar o plano, salvo quando ele já fornecer um plano aprovado ou autorizar expressamente a criação imediata.

### Etapa 2 — produzir e verificar

Após a aprovação:

1. Construir a apresentação conforme o plano aprovado e o contrato dos slides.
2. Aplicar a formatação pedida pelo usuário (por exemplo, a skill `apresentacao-bullets`), se houver.
3. Renderizar o formato solicitado.
4. Auditar como leitor frio, sempre depois da última passada de formatação.
5. Corrigir os problemas encontrados antes de entregar.

Se o pedido for apenas de planejamento, análise ou revisão, limitar-se à etapa correspondente e não inferir autorização para criar ou alterar arquivos.

## Executar as cinco fases

### 1. Localizar a aula no curso

Determinar:

- público, nível de formação e conhecimentos prévios razoáveis;
- duração total, intervalo e tempo efetivo de exposição e atividades;
- conteúdos anteriores dos quais a aula depende;
- conteúdo previsto para a data e bibliografia correspondente;
- aulas seguintes para as quais a exposição deve construir uma ponte;
- profundidade compatível com o curso e com eventuais avaliações ou seleções acadêmicas.

Formular uma pergunta orientadora capaz de organizar toda a aula. Definir objetivos de aprendizagem observáveis, evitando verbos vagos quando for possível especificar o desempenho esperado.

### 2. Reconstruir a arquitetura argumentativa da fonte

Produzir internamente um mapa de cobertura para cada núcleo do texto:

| Elemento | Pergunta de controle |
|---|---|
| Problema | Que pergunta o autor procura responder? |
| Premissas | De quais definições, hipóteses e condições o argumento depende? |
| Mecanismo | Por quais etapas lógicas, matemáticas ou causais se chega ao resultado? |
| Resultado | Qual proposição ou conclusão foi estabelecida? |
| Interpretação | O que o resultado significa na linguagem da disciplina? |
| Limites | Em que condições o resultado deixa de valer ou não responde à questão normativa? |
| Conexão | Por que esse resultado exige o próximo tópico? |

Registrar páginas, seções ou localizadores da fonte para cada núcleo. Preservar a ordem lógica do autor quando ela for pedagogicamente necessária; reorganizar apenas quando isso melhorar a compreensão sem deformar o argumento.

Não considerar um tópico coberto se a apresentação mostrar apenas sua conclusão. Expor as premissas e o mecanismo necessários para que o estudante possa reconstruí-la.

### 3. Diagnosticar pré-requisitos e montar o inventário de conceitos

Identificar o que a fonte presume que o estudante já sabe, incluindo:

- conceitos e distinções terminológicas;
- notação, identidades e resultados matemáticos;
- modelos anteriores;
- instituições e episódios históricos;
- debates normativos ou metodológicos;
- convenções gráficas e formas de interpretar diagramas.

Registrar tudo no inventário de conceitos, uma linha por item que aparecerá em lâmina:

| Item | Tipo | Definição em uma frase | Origem | Localizador | Lâmina em que é definido | Tratamento |
|---|---|---|---|---|---|---|
| termo técnico, sigla, nome próprio, modelo, tese ou afirmação empírica | conceito, modelo ou tese, autor, evidência, norma | como o estudante a lerá | autor, ano e obra; ou a aula anterior em que foi ensinado | página ou seção da fonte | sempre anterior ou igual à do primeiro uso | completo, retomada breve, apêndice ou corte |

O inventário está completo quando todo termo técnico, sigla, nome próprio, modelo e afirmação empírica previsto para as lâminas tem uma linha, e toda linha tem definição, origem e lâmina de definição, ou está marcada como corte.

Explicar o pré-requisito antes de usá-lo. Calibrar a extensão ao nível da turma: retomar brevemente conteúdos já dominados e desenvolver os indispensáveis que não possam ser presumidos.

### 4. Selecionar complementos relevantes

Complementar a fonte quando isso permitir compreender melhor o que está sendo afirmado, por que o argumento surgiu ou quais são seus limites. Considerar:

- origem e evolução das ideias;
- localização dos autores em escolas, universidades e tradições intelectuais;
- controvérsias teóricas ou empíricas;
- derivações formais omitidas pelo manual;
- hipóteses, evidências e magnitudes que o manual menciona sem especificar;
- exemplos institucionais ou aplicações empíricas;
- esclarecimentos terminológicos e analogias controladas.

Aplicar o teste de relevância: manter o complemento somente se ele ajudar a responder **o que**, **por quê**, **como** ou **sob quais limites**. Evitar biografias ornamentais, cronologias desconectadas e exemplos que substituam o argumento em vez de esclarecê-lo.

Priorizar fontes primárias, documentos oficiais, páginas institucionais e literatura acadêmica. Distinguir, no processo de elaboração:

- **F — fonte principal:** argumento ou evidência da leitura-base;
- **C — complemento:** explicação ou evidência adicionada para fins didáticos;
- **I — interpretação:** síntese ou conexão formulada pelo professor.

Não exigir que esses rótulos apareçam visualmente em todos os slides; usar a distinção para evitar atribuições indevidas e tornar explícita a atribuição quando houver risco de ambiguidade.

### 5. Converter o argumento em sequência pedagógica

Organizar, como padrão adaptável:

1. pergunta orientadora e motivação;
2. objetivos e mapa lógico;
3. localização da fonte, dos autores e do problema;
4. apresentação dos conceitos e pré-requisitos;
5. desenvolvimento progressivo do argumento;
6. sínteses intermediárias;
7. exemplos, diagramas ou exercícios analíticos;
8. aplicação integradora;
9. síntese final e verificação de aprendizagem: pergunta curta e individual, respondível com o que foi exposto, com resposta esperada preparada;
10. apêndice técnico e referências, quando necessário.

Orçar as lâminas pelo inventário antes de redigir: um modelo ou tese nomeada precisa de espaço para pergunta, hipóteses, mecanismo, resultado e limites. Quando a duração não comportar todos os itens com esse tratamento, propor ao usuário o que cortar, encurtar ou mover para o apêndice; a escolha entre cobertura e profundidade é dele e aparece no plano.

Distribuir o tempo antes de redigir os slides. Incluir intervalos e atividades na soma. Ajustar a quantidade de slides à densidade do conteúdo, ao ritmo da exposição e ao sistema visual fornecido; não buscar um número arbitrário de lâminas.

Registrar os tempos somente no plano pedagógico. Não exibir minutos, durações ou horários nas lâminas — agenda, títulos, rótulos de atividade — nem nas notas do apresentador, salvo pedido explícito do usuário.

Se houver tempo para avançar além do trecho principal, seguir a sequência do plano de ensino e construir apenas uma ponte controlada. Não esvaziar aulas futuras antecipando seus argumentos em detalhe.

## Cumprir o contrato dos slides

Ler [`references/contrato-da-lamina.md`](references/contrato-da-lamina.md) antes de redigir ou revisar lâminas: traz a estrutura de cada tipo e exemplos de antes e depois.

### Título e abertura

Usar um título curto e específico, que nomeie o objeto da lâmina: o conceito, o modelo com autor e ano, a pergunta, a comparação. Um título que afirma cabe em lâminas de evidência e de síntese. Em aula existente, manter os títulos temáticos e corrigir apenas os vagos ("Contexto", "Visão geral") e os que tragam nome ou termo que a lâmina não apresenta.

A abertura é a primeira linha de conteúdo da lâmina e depende do tipo:

| Tipo de lâmina | Abre com | Mostra em seguida |
|---|---|---|
| Conceito | a definição do termo | origem, quando o termo tem autor ou história; exemplo; diferença para o conceito vizinho |
| Modelo, teorema ou tese | a pergunta que ele responde | autor, ano e obra; hipóteses nomeadas; mecanismo; resultado; interpretação |
| Limites ou crítica | o resultado retomado e a pergunta sobre quando ele deixa de valer | cada limite ao lado da hipótese que falha |
| Evidência ou gráfico | o achado | quem mediu, onde, quando e quanto; fonte visível |
| Instituição ou norma | o que a regra determina | base legal, vigência e quem é afetado |
| Síntese | a afirmação central | apenas termos já definidos |
| Atividade | a tarefa | os dados necessários para resolvê-la |

A abertura só afirma o que o estudante consegue entender e conferir com o que já foi exibido. Uma conclusão que dependa de definições ou hipóteses ainda não mostradas fecha a lâmina, depois delas.

### Dependência e ligação

Em cada slide substantivo:

- definir cada termo técnico, sigla e nome próprio na lâmina em que aparece pela primeira vez, ou antes; o termo ensinado em aula anterior é marcado como retomada, com a aula;
- mostrar as hipóteses antes do resultado que depende delas;
- escrever a frase de ligação quando a lâmina reunir dois conceitos: dizer por que um leva ao outro;
- preservar uma conexão clara com o slide anterior e o seguinte;
- desenvolver um argumento identificável, não apenas nomear um assunto;
- limitar a informação ao que possa ser lido e explicado com legibilidade;
- repartir argumentos longos entre slides consecutivos sem quebrar sua cadeia lógica.

Fazer toda frase de efeito vir depois da explicação que a sustenta. Evitar listas genéricas e slides cuja compreensão dependa de informação não exibida.

Manter nos slides:

- argumentos centrais da fonte;
- hipóteses e condições indispensáveis;
- resultados e interpretações essenciais;
- fórmulas, diagramas ou evidências necessários ao raciocínio;
- distinções cuja omissão possa gerar erro conceitual.

Usar diagramas, tabelas e gráficos apenas quando tiverem função analítica explícita. Recriar representações de maneira limpa e atribuir a ideia correspondente; não copiar figuras protegidas quando uma reconstrução original for suficiente.

Esta skill decide o que a lâmina afirma, em que ordem e com que fontes. Níveis de bullet, rótulos e pontuação seguem a convenção do deck ou a skill `apresentacao-bullets`, quando usada.

### Apresentar modelos, teoremas e teses

Ao introduzir um modelo, um teorema ou uma tese com nome de autor:

1. formular a pergunta que ele resolve;
2. dizer quem o formulou, quando, em que obra e a que debate respondia;
3. definir objetos, agentes e notação;
4. enunciar as hipóteses uma a uma, pelo nome;
5. desenvolver a intuição ou derivação suficiente para o nível da turma;
6. apresentar o resultado;
7. interpretá-lo economicamente;
8. mostrar os limites, cada um ligado à hipótese cuja falha o produz.

Não apresentar convexidade, racionalidade, equilíbrio, identificação ou outras hipóteses como requisitos genéricos intercambiáveis. Associar cada hipótese ao resultado para o qual ela é necessária.

Explicar cada fórmula em palavras: definir os símbolos, indicar a relação econômica expressa, mostrar como o resultado muda quando os elementos relevantes variam e esclarecer o que não pode ser concluído a partir dela.

### Mostrar as fontes em duas camadas

Ler [`references/fontes-e-evidencia.md`](references/fontes-e-evidencia.md) ao citar autor, apresentar evidência ou incluir figura ou tabela.

- **Camada visível, na lâmina:** autor e ano junto de todo conceito com origem, modelo, tese, evidência e citação; linha de fonte em toda figura e tabela, com a classe do material (dado real, figura adaptada ou exemplo hipotético).
- **Camada de conferência, nas notas:** referência completa, página, trecho citado, classe F, C ou I, cálculos próprios e ressalvas.

Apresentar evidência com quem mediu, onde, quando e quanto. Resolver toda referência indeterminada ("sob certas hipóteses", "a evidência mostra", "na literatura") no item que ela esconde.

### Construir exercícios e aplicações

Fazer os exercícios decorrerem das condições e mecanismos já apresentados. Incluir informação suficiente para resolvê-los e preparar solução verificável. Variar entre:

- identificação de hipótese ou mecanismo;
- interpretação de gráfico ou expressão;
- derivação curta;
- comparação de casos;
- diagnóstico institucional;
- questão integradora semelhante à avaliação esperada.

Não introduzir na atividade um conceito indispensável que não tenha sido explicado antes.

## Adotar as convenções de linguagem

Redigir em português do Brasil todo o material voltado ao estudante. Nomear os momentos da aula com termos em português, não com anglicismos:

| Evitar | Usar |
|---|---|
| exit ticket | verificação de aprendizagem |
| warm-up | aquecimento ou pergunta inicial |
| roadmap | roteiro da aula |
| recap | retomada |
| takeaways, wrap-up | síntese ou fechamento |
| hands-on | atividade prática |

Manter em inglês apenas o termo técnico consagrado na disciplina (por exemplo, *trade-off* ou *spillover*), em itálico e explicado na primeira ocorrência.

## Elaborar o plano pedagógico para aprovação

Apresentar um plano suficientemente específico para orientar a implementação sem novas decisões. Incluir:

- síntese e pergunta orientadora;
- público, pressupostos e duração;
- arquitetura da aula por blocos, com tempo e número aproximado de slides;
- cadeia argumentativa e principais conceitos, modelos ou evidências;
- inventário de conceitos, com o tratamento de cada item e os cortes propostos;
- complementos previstos e sua função didática;
- exercícios, aplicação e fechamento;
- estratégia visual e uso do template indicado;
- entregáveis e critérios de aceitação;
- avanço eventual para conteúdos seguintes e seu limite.

Não usar o plano como substituto da pesquisa. Basear suas escolhas na inspeção efetiva das fontes e informar limitações de acesso ou qualidade documental.

## Produzir no formato solicitado

Usar a skill específica do formato em conjunto com esta skill quando houver criação de PPTX, Quarto, PDF ou outro artefato. Se a entrega for Quarto para PowerPoint:

- preservar o `.qmd` como fonte reproduzível;
- usar o `reference-doc` solicitado ou derivado do template fornecido;
- verificar a compatibilidade dos layouts exigidos pelo mecanismo de renderização;
- preservar a identidade visual e substituir fontes somente conforme instruído;
- manter fórmulas e elementos gráficos legíveis e editáveis quando possível;
- renderizar e inspecionar o PPTX resultante, não apenas o código-fonte.

Tratar as instruções visuais do usuário e o template como restrições concretas. Não reproduzir mecanicamente a densidade ou a estrutura de uma apresentação anterior quando isso prejudicar o novo argumento.

## Adaptar para revisão de uma aula existente

Quando o usuário pedir revisão:

1. Comparar o plano de ensino, a fonte-base e os slides.
2. Construir uma matriz de cobertura com argumento, fonte, slide e lacuna.
3. Auditar como leitor frio para localizar termos sem definição, resultados sem hipóteses, evidência sem estudo e figuras sem fonte.
4. Identificar erros conceituais, contexto irrelevante, exercícios insolúveis e problemas de tempo ou legibilidade.
5. Relatar o diagnóstico com evidências antes de alterar arquivos, salvo quando a solicitação incluir explicitamente a correção.

## Auditar como leitor frio

O leitor frio tem apenas as lâminas renderizadas, sem as notas, a fonte e o plano: é a posição do estudante. Seguir o protocolo de [`references/auditoria.md`](references/auditoria.md), que percorre cada lâmina substantiva e registra, com o trecho literal:

- se a abertura corresponde ao tipo da lâmina;
- onde cada termo, sigla e nome próprio novo é definido;
- se as hipóteses estão nomeadas e antes do resultado;
- se cada evidência traz estudo, lugar, período e magnitude;
- se cada figura e tabela tem linha de fonte inteira e classe, e se os números do texto conferem com ela;
- se resta alguma referência indeterminada;
- se a ligação com a lâmina anterior está escrita.

Depois, conferir a rastreabilidade nas notas e a lista de tempo e artefato do mesmo arquivo.

A aula está concluída quando toda lâmina substantiva tem linha na tabela de auditoria e nenhuma linha tem falha aberta. Falhas que dependam de decisão do usuário (um corte, uma fonte inacessível) vão para o relatório. Registrar no encerramento os arquivos produzidos, a duração, o número de slides, o resumo da auditoria e as verificações que não puderam ser feitas.
