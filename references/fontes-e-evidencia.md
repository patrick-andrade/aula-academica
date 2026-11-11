# Fontes e evidência

## Duas camadas

O estudante confere a origem do que lê na própria lâmina; o professor confere o detalhe nas notas.

| Camada | Onde | O que traz |
|---|---|---|
| Visível | lâmina | autor e ano junto de conceito com origem, modelo, tese, evidência, citação e dado; linha de fonte em figura e tabela |
| Conferência | notas do apresentador | referência completa, página ou seção, trecho citado, classe F, C ou I, cálculos próprios e ressalvas |

Na lâmina, a citação é curta: `Tiebout (1956)`, `Receita Federal (2025)`. Todo autor e ano visível tem a referência completa na bibliografia da aula ou numa lâmina de referências ao final; o estudante não vê as notas.

## Citar o que foi lido

Registrar nas notas como cada obra chegou à aula:

- obra consultada: referência completa e página;
- obra conhecida pela fonte-base: "Tiebout (1956), conforme Stiglitz e Rosengard (2015, p. 810-812)".

Na lâmina, a origem da ideia aparece como autor e ano nos dois casos. Uma lista de hipóteses, um número ou uma citação literal só entram como sendo do autor original quando conferidos na obra dele; do contrário, a lâmina atribui à fonte-base ("segundo Stiglitz e Rosengard (2015), Tiebout supõe…").

## Linha de fonte em figuras e tabelas

Toda figura e toda tabela traz uma linha de fonte visível, que diz também a classe do material:

| Classe | Quando | Linha visível |
|---|---|---|
| Dado real | os números vêm de fonte publicada | `Fonte: Receita Federal (2025), Tabela 2. Elaboração própria.` |
| Figura adaptada | a figura de uma obra foi redesenhada, com ou sem mudança | `Adaptado de Stiglitz e Rosengard (2015), Figura 26.4.` |
| Exemplo hipotético | os números foram criados para ilustrar o argumento | `Exemplo hipotético. Elaboração própria.` |
| Quadro do professor | síntese ou comparação montada para a aula | `Elaboração própria, a partir de Stiglitz e Rosengard (2015).` |

Combinar as classes quando for o caso: `Adaptado de Stiglitz e Rosengard (2015), Figura 26.4. Valores hipotéticos.`

Quando o dado real for estimativa ou simulação de terceiros, dizer isso na linha: `Fonte: Gobetti e Monteiro (2023), Tabela 1 (simulação com a receita de 2022). Elaboração própria.`

Regras de aplicação:

- Pôr a linha dentro da própria figura (a legenda do gráfico, como `labs(caption = )` no ggplot2), para que ela acompanhe a imagem em qualquer layout.
- Quebrar a linha longa em duas: a legenda que passa da largura da figura sai cortada. Conferir na saída renderizada que ela aparece inteira.
- Em tabela, usar a legenda da tabela ou uma linha logo abaixo, conforme o que o template renderiza; conferir na saída.
- Conferir que os números citados no texto ao lado são os que a figura mostra, na mesma unidade; quando a unidade diferir (governos estaduais no texto, unidades da federação no gráfico), dizer as duas.
- Informar o ano dos dados e a unidade no eixo, no título ou na linha de fonte.
- Quando a figura junta fontes ou anos diferentes, nomear todos e dizer nas notas o que isso limita na comparação.
- Dizer "elaboração própria" quando o desenho ou o cálculo for do professor, mesmo com dados de terceiros.

## Padrão de evidência

Uma afirmação empírica na lâmina traz:

1. **quem** mediu: autor e ano;
2. **onde e quando**: país ou região, período e unidade observada (municípios, famílias, empresas);
3. **quanto**: a magnitude, com unidade;
4. **como**: o tipo de evidência em poucas palavras (descrição, correlação, experimento, estimativa causal);
5. **ressalva**: a limitação mais importante, quando ela mudar a leitura do resultado.

Quando a fonte-base afirmar o resultado sem magnitude, buscar o estudo original. Se ele não estiver acessível, escrever o que a fonte-base afirma, atribuir a ela e registrar nas notas que a magnitude não foi localizada.

Havendo evidência para o país da turma, mostrá-la junto da evidência internacional.

## Referências indeterminadas

Cada expressão abaixo esconde um item que a lâmina deve mostrar:

| Expressão | O que escrever no lugar |
|---|---|
| "sob certas hipóteses", "em determinadas condições" | as hipóteses, pelo nome |
| "a evidência mostra", "estudos indicam" | o estudo, o lugar, o período e a magnitude |
| "na literatura", "os economistas" | o autor e o ano, ou a escola |
| "muitos países", "em geral" | quantos, quais ou a fonte da contagem |
| "recentemente", "nos últimos anos" | o ano ou o período |
| "segundo a teoria" | o modelo ou o autor |

Quando a vagueza vier da própria fonte-base, resolver pela obra original (fase 4) em vez de traduzi-la.
