<h1>Copiar, Colar e Deletar</h1>

É importante lembrar que você tem que estar no modo normal.

<h2>Copiar e Colar</h2>

Utlizamos o <b>y</b> para copiar e o <b>p</b> para colar. Uma observação que legal comentar e que <i>y</i> vem de <i>"yank"</i> e o <i>p</i> de <i>"paste"</i>.

<b>yy ............ </b><i>para copiar uma linha inteira</i>

A maneira mais fácil de fazer um copy&paste é entrar no modo visual(v), selecionar o texto e pressionar o <i>y</i>

<h2>Deletando</h2>

<b>x ............... </b><i>deleta o caractere onde o cursor estiver</i>
 
<b>X ............... </b><i>deleta o caractere de trás do cursor</i>

<b>dw ............ </b><i>deleta a partir do cursor até o começo da próxima palavra</i>

<b>d$ ............. </b><i>deleta do cursor até o fim da linha</i>

<b>dd ............. </b><i>deleta a linha inteira</i>

<b>C ............... </b><i>deleta de onde o cursor estiver até o final da linha e entra em modo de inserção a partir dali</i>

<b>ce ............. </b><i>deleta do cursor até o final da palavra e entra em modo de inserção</i>

<h2>Recortar e Colar</h2>

Quando deletamos um conteúdo no Vim, esse conteudo é armazenado na memória, ou seja usamos alguma tecla de exclução <i>(d,dd,dw etc)</i> para recortar, agora é só mover o cursor até o local onde deseja colar e usar o <i>p</i>

<h2>Clipboard</h2>

Para colar textos da área de transferência usando os comandos:

<b>^Insert ................... </b><i>copia a área selecionada</i>

<b>Shift + Insert ......... </b><i>cola o que está no clipboard</i>

<b>^Delete ................... </b><i>recorta para o clipboard</i>

<h2>Desfazendo</h2>

Se você cometer um erro, não se preocupe! Use um desses comandos:

<b>u ............... </b><i>para desfazer</i>

<b>U .............. </b><i>para desfazer mudanças na última linha editada</i>

<b>^r ............... </b><i>para refazer</i>


<blockquote><a href="../referencias/fontes-recomendacoes.md">Fontes e Recomendações</a><blockquote>