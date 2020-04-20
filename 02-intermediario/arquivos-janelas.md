<h1>Arquivos e Janelas</h1>

<h2>Arquivos</h2>

Para abrirmos mais de um arquivo por vez, podemos fazer o seguinte comando

```shell
vim -O nomeArquivo.txt outroArquivo.txt
```

com isso, o Vim ira abrir os arquivos em duas janelas verticais, para janelas horizontais basta substituir o <b>-O</b> por <b>-o</b>. Se você omitir o <b>-o/-O</b> o Vim esses arquivos serão abertos do mesmo jeito, mas apenas em uma janela, para alterar entre uma e outra tera de usar <b>^ww</b>.

Outra forma possivel, ja dentro do Vim, é usando <b>:edit</b> ou <b>:e</b> e passando o diretorio.

```shell
:e /home/luan/Desktop/nomeArquivo.txt
```

<h2>Janelas</h2>

O Vim permite fazer uma divisão de janelas, assim conseguimos trabalhar em diversos arquivos de uma vez.

Podemos abrir janelas na horizontal quanto na vertical, e é simples.

<b>:vsp /home/luan/Desktop/nomeArquivo.txt ............... </b><i>vertical</i>

<b>:sp /home/luan/Desktop/nomeArquivo.txt ................. </b><i>horizontal</i>

Para movermos entre uma janela e outra, usamos:

<b>^w + tecla de direcao ................. </b>move entre as janelas

<b>^wo .............................................. </b>somente essa janela, fecha todas as outras

<b>^w+ .............................................. </b>aumenta o tamanho da janela

<b>^w- ............................................... </b>diminui o tamanho da janela

<b>^w= .............................................. </b>deixa todas as janelas com tamanhos iguais


<blockquote><a href="../referencias/fontes-recomendacoes.md">Fontes e Recomendações</a></blockquote>