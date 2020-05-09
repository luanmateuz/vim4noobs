<h1>Buscas e Substituições</h1>

É importante lembrar que você tem que estar no modo normal.

<h2>Buscas</h2>

Para fazer uma busca, basta pressionar "<b>/</b>", e digitar. Automaticamente o Vim irá procurar pelo conteúdo digitado.

Você também pode usar Expressões Regulares para fazer suas buscas.

<h2>Substituições</h2>

Agora que aprendemos a fazer buscas, podemos substituir. Para fazermos substituições temos alguns comandos:

<b>:s/velho/novo ............ </b><i>substitui a 1ª ocorrência de velho por novo na linha corrente</i>

<b>:% s/velho/novo ........ </b><i>substitui em todo o arquivo (%) a 1ª ocorrência de velho por novo em cada linha</i>

<b>:% s/velho/novo/g ..... </b><i>substitui em todo o arquivo (%), todas (g) as ocorrências de velho por novo</i>

<b>:% s/velho/novo/gc .... </b><i>igual ao anterior, mas pedindo confirmação para cada substituição</i>

<b>OBS: </b>expressões regulares também funcionam.

<blockquote><a href="../referencias/fontes-recomendacoes.md">Fontes e Recomendações</a><blockquote>