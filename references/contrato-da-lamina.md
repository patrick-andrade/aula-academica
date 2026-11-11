# Contrato da lâmina

Cada lâmina substantiva tem um tipo, e o tipo define a abertura: a primeira linha de conteúdo abaixo do título. A regra que vale para todos os tipos é a de dependência: a abertura só afirma o que o estudante consegue entender e conferir com o que já foi exibido. Os exemplos mostram o conteúdo e a ordem; a forma dos bullets segue a convenção do deck.

## Conceito

Abre com a definição: o que é a coisa e o que a distingue das vizinhas. Em seguida, a origem (autor, ano e obra, ou a história do termo), um exemplo e a ligação com o conceito de que a aula tratará a seguir.

Antes:

~~~markdown
## Bens públicos nacionais e locais

- Cada bem público deve caber ao nível de governo que alcança todos os seus beneficiários
- Federalismo fiscal: a divisão de responsabilidades econômicas entre os níveis de governo
- Dois tipos

    - nacionais: beneficiam todo o país
    - locais: beneficiam só quem vive na localidade
~~~

A lâmina abre com uma conclusão normativa, define "federalismo fiscal" sem ter definido federação e deixa "Dois tipos" sem dizer de quê. Nada liga os bens públicos ao federalismo.

Depois, em duas lâminas:

~~~markdown
## Federação e federalismo fiscal

- Federação: Estado em que a Constituição reparte o poder entre níveis de governo autônomos, cada um com tributos e gastos próprios
- Federalismo fiscal: o estudo de qual nível de governo deve gastar e tributar em quê
- Pergunta do bloco: que critério decide o nível de governo de cada gasto?

## Bens públicos nacionais e locais

- Os bens públicos diferem pelo alcance geográfico do benefício

    - nacionais: beneficiam todo o país, como a defesa
    - locais: beneficiam só quem vive na localidade, como a iluminação das ruas

- Esse alcance é o critério do federalismo fiscal: o nível de governo adequado é o que reúne todos os beneficiários do bem
- Por isso, a defesa cabe ao governo nacional e a iluminação, ao município
~~~

A afirmação que abria a lâmina original agora fecha a segunda, depois das definições que ela usa. A frase "Esse alcance é o critério…" é a frase de ligação entre os dois conceitos.

## Modelo, teorema ou tese

Abre com a pergunta que o modelo responde. Em seguida: quem o formulou, quando e em que obra; as hipóteses, uma a uma; o mecanismo; o resultado; a interpretação. Um nome próprio no título pede que a lâmina diga quem é.

Antes:

~~~markdown
## Tiebout: votar com os pés

- A concorrência entre comunidades pode levar à provisão eficiente de bens públicos locais
- Mecanismo

    - cada comunidade oferece um pacote de bens públicos e tributos
    - as famílias escolhem onde morar

- Resultado: sob certas hipóteses, a alocação é eficiente
- Hipóteses

    - muitas comunidades
    - mudança sem custo
~~~

O título traz um nome que a lâmina não apresenta, o resultado vem antes das hipóteses e "sob certas hipóteses" não diz quais.

Depois:

~~~markdown
## O modelo de Tiebout (1956): votar com os pés

- Pergunta: há um mecanismo que revele quanto as pessoas querem de cada bem público local?
- Charles Tiebout, economista americano, respondeu que sim no artigo "A pure theory of local expenditures" (1956)
- Hipóteses

    - muitas comunidades, cada uma com seu pacote de bens públicos e tributos
    - famílias plenamente informadas, que se mudam sem custo
    - nenhum efeito do gasto de uma comunidade sobre as outras

- Mecanismo

    1. cada família escolhe a comunidade cujo pacote prefere
    2. por isso, a comunidade que oferece o que as famílias querem atrai moradores
    3. logo, cada pacote acaba reunindo quem o prefere

- Resultado: com essas três hipóteses, a oferta de bens públicos locais é eficiente
~~~

Se o conteúdo não couber com legibilidade, repartir em duas lâminas consecutivas no ponto em que a cadeia admite pausa: pergunta, origem e hipóteses na primeira; mecanismo e resultado na segunda.

## Limites ou crítica

Abre retomando o resultado e perguntando quando ele deixa de valer. Cada limite aparece ao lado da hipótese cuja falha o produz, para que o estudante veja de onde vem.

Antes:

~~~markdown
## Limites da descentralização

- As hipóteses de Tiebout raramente valem
- Transbordamentos: poluição que atinge o vizinho
- Concorrência limitada: poucas comunidades
~~~

Depois:

~~~markdown
## Quando o resultado de Tiebout falha

- O resultado depende de três hipóteses; cada uma, quando falha, gera um limite da descentralização

| Hipótese | Quando falha | Consequência |
|---|---|---|
| nenhum efeito sobre outras comunidades | a poluição de uma cidade atinge a vizinha | a comunidade ignora o dano e oferta o bem em nível ineficiente |
| muitas comunidades | há poucas opções de moradia na região | a concorrência não disciplina o governo local |
| mudança sem custo | emprego e família prendem as pessoas | o morador insatisfeito fica onde está |
~~~

## Evidência ou gráfico

Abre com o achado, porque a figura ou o estudo o sustenta na própria lâmina. Em seguida: quem mediu, onde, quando e quanto. A figura traz a linha de fonte (ver [`fontes-e-evidencia.md`](fontes-e-evidencia.md)).

Antes:

~~~markdown
- Evidência: o gasto local reage bem mais à transferência do que à renda
~~~

Depois:

~~~markdown
- Cada R$ 1 de transferência eleva o gasto local em R$ [x]; cada R$ 1 de renda dos moradores, em R$ [y]
- Medida: [autor] ([ano]), com dados de [lugar e período]
- Ressalva: [limitação que o próprio estudo ou a literatura aponta]
~~~

Os colchetes marcam o que precisa vir da fonte. Sem magnitude disponível, escrever o que a fonte afirma e dizer que ela não quantifica.

## Instituição ou norma

Abre com o que a regra determina. Em seguida: base legal, vigência, quem é afetado e o que muda em relação à regra anterior.

~~~markdown
- Os estados entregam aos seus municípios 25% do ICMS arrecadado
- Base legal: Constituição de 1988, art. 158, IV
- Repartição: ao menos 65% pelo valor adicionado em cada município
~~~

## Síntese

Abre com a afirmação central do bloco ou da aula e usa apenas termos já definidos. É o lugar das frases de efeito: a explicação que as sustenta já foi dada.

## Atividade

Abre com a tarefa e traz os dados necessários para resolvê-la. A resposta esperada fica nas notas.

## Lâminas que não entram no contrato

Capa, divisor de seção, roteiro, bibliografia e encerramento não têm abertura a conferir.
