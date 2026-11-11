# Auditoria como leitor frio

O leitor frio tem apenas as lâminas renderizadas. Não leu a fonte, o plano nem as notas do apresentador: é a posição do estudante. A auditoria roda depois da última passada de formatação e tem três passadas.

## Preparar a visão do estudante

1. Renderizar a apresentação no formato final.
2. Extrair o que aparece nas lâminas, sem as notas: exportar para PDF ou imagens e ler essa saída, não o arquivo-fonte.
3. Numerar as lâminas pela saída renderizada.

## Passada 1 — leitor frio, sem notas

Entregar a visão do estudante a um revisor independente: um subagente sem acesso à conversa, à fonte e às notas, quando o ambiente oferecer; do contrário, uma passada própria que consulte apenas a saída renderizada. O revisor preenche uma linha por lâmina substantiva:

| Coluna | O que registrar | Passa quando |
|---|---|---|
| Lâmina | número e título | — |
| Tipo | conceito, modelo ou tese, limites, evidência ou gráfico, instituição ou norma, síntese, atividade | — |
| Abertura | a primeira linha, literal | corresponde ao tipo e só usa o que já foi exibido |
| Termos novos | cada termo técnico, sigla e nome próprio que aparece pela primeira vez | cada um está definido nesta lâmina ou em anterior, com a lâmina indicada |
| Hipóteses | as hipóteses do resultado apresentado | estão nomeadas uma a uma e vêm antes do resultado |
| Evidência | cada afirmação empírica | traz autor, ano, lugar, período e magnitude |
| Figura ou tabela | a linha de fonte, literal, lida na imagem renderizada | existe, aparece inteira e diz a classe: dado real, figura adaptada, exemplo hipotético ou quadro do professor |
| Conta e figura | cada número ou conclusão que a lâmina tira de uma figura ou de uma conta | confere com a figura ao lado e com a conta exibida, na mesma unidade |
| Referências indeterminadas | cada ocorrência, literal | não há nenhuma |
| Ligação | a frase que conecta à lâmina anterior ou ao conceito anterior | está escrita na lâmina, não só na fala |
| Veredito | passa, ou a lista das falhas | — |

Cada falha traz o trecho literal e o que falta. Uma coluna que não se aplica à lâmina recebe "não se aplica".

Perguntas de controle para o revisor, ao final:

- Que termos eu precisaria perguntar ao professor para entender esta aula?
- Em que lâmina uma conclusão aparece sem que eu saiba de onde veio?
- Que figura eu não saberia dizer se mostra dado real ou exemplo?
- Que autores citados nas lâminas não aparecem na bibliografia nem numa lâmina de referências?

Um termo ensinado em aula anterior passa quando a lâmina o marca como retomada, com a aula ("problema do carona, aula 5"). O revisor não presume o que a turma já sabe.

## Passada 2 — rastreabilidade, com notas

Com as notas abertas, conferir:

- cada "Autor (ano)" visível tem referência completa e página nas notas;
- cada obra conhecida só pela fonte-base está registrada como tal;
- cada número da lâmina confere com a fonte indicada, e os cálculos próprios estão descritos;
- argumentos da fonte, complementos e interpretações não foram atribuídos indevidamente;
- limitações e divergências relevantes estão registradas.

## Passada 3 — tempo e artefato

- A soma dos tempos, incluindo intervalo e atividades, corresponde à duração solicitada.
- As lâminas e as notas do apresentador estão livres de minutos e durações.
- O volume de conteúdo é compatível com o ritmo de uma aula real.
- Os termos voltados ao estudante estão em português, sem anglicismos desnecessários.
- Os exercícios podem ser resolvidos com o conteúdo apresentado.
- A aula se conecta ao curso sem repetir ou antecipar indevidamente outras aulas.
- O arquivo final foi renderizado e inspecionado integralmente.
- Não há cortes, sobreposições, fontes tipográficas indevidas, elementos fora da área ou fallback de layout.

## Corrigir e repetir

Corrigir as falhas na fonte da apresentação, renderizar de novo e repetir a passada 1 nas lâminas alteradas e nas vizinhas. A auditoria termina quando toda lâmina substantiva tem linha na tabela e nenhuma linha tem falha aberta.

Levar ao relatório final:

- o número de lâminas auditadas e de falhas corrigidas, por coluna;
- as falhas que dependem de decisão do usuário, como um corte ou uma fonte inacessível;
- as lâminas ou passadas que não puderam ser verificadas, e o motivo.
