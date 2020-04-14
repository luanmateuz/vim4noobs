<h1>Configurando o Vim</h1>

O Vim puro, não e muito legal, por isso vamos fazer um .vimrc para podermos configurar o nosso editor, e instalar temas e plugins.

<h2>.vimrc</h2>

Primeiros vamos acessar o nosso arquivo. Se você não tiver o .vimrc, acabamos de cria-lo.

```shell
vim ~/.vimrc
```


Vamos fazer uma configuração simples, logo, logo entenderá o porque.
Agora que já estamos com o .vimrc aberto iremos edita-lo.

```vim
" Ativa a numeração das linhas
set number
"
" Habilita o destaque de sintaxe
syntax enable
"
" Desativa a quebra de linha automática (comentado por padrão)
set nolinebreak
"
" Insere espaços no lugar de caracteres de tabulação
set expandtab
"
" Uso inteligente de tabulações
set smarttab
"
" Define uma tabulação como sendo oito espaços
set shiftwidth=8
set tabstop=8
```

Essas configurações são  pessoais, então olhe a de outras pessoas para poder fazer o seu, leia esses posts, eles vão te ajudar:
<ul>
  <li><a href="https://www.vivaolinux.com.br/etc/vimrc-2/">.vimrc - Viva o Linux</a></li>
  <li>
 <a href="https://pt.wikibooks.org/wiki/Vim/Como_editar_prefer%C3%AAncias">Como editar preferencias - WikiBooks</a></li>
  <li><a href="https://dougblack.io/words/a-good-vimrc.html">A goo vimrc - Doug Black</a></li>
</ul>

Caso você tenha preguiça de fazer, esses sites vão facilitar muito sua vida:
<ul>
  <li><a href="https://vimconfig.com/">Vim Config</a></li>
  <li><a href="https://vim-bootstrap.com/">Vim Bootstrap</a></li>
</ul>

<h2>Temas</h2>

Podemos instalar temas atraves de um arquivo ou plugin, os procedimentos são bastante iguais.

Confira alguns temas aqui:
<ul>
  <li><a href="https://github.com/rafi/awesome-vim-colorschemes">Awesome Vim Colorschemes</a></li>
  <li><a href="http://vimcolors.com/">Vim Colors</a></li>
</ul>

Será necessário criar uma a pasta ∼/.vim , se a mesma ainda não existir.

Os temas podem ser clonados dentro de ∼/.vim/colors para melhor organização.

Normalmente, na documentação do próprio tema tem um passo a passo de instalação, mas
basicamente você sempre vai fazer:

```shell
cd ~/.vim/colors
git clone esquemadecores.git
```
E adicionar a linha do esquema no seu .vimrc .

```vim
colorscheme esquemadecores
```
<h2>Plugins</h2>

Para instalar plugins no Vim, precisamos usar uma ferramenta, o Vundle ou Plug. Aqui utilizaremos o Vundle. Vamos lá:

1. Abra o terminal e execute:
```shell
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```

2. Adicione isso no seu .vimrc

```vim
" set the runtime path to include Vundle and initialize 
set rtp+=~/.vim/bundle/Vundle.vim
call vundle#begin()
" let Vundle manage Vundle, required
Plugin 'VundleVim/Vundle.vim'
call vundle#end()            " required
```
Agora ja temoso Vundle instalado, so precisamos adicionar os plugins.

Site com varios plugins para o Vim:

<ul>
  <li><a href="https://vimawesome.com/">Vim Awesome</a></li>
</ul>

Nesse exemplo vou instalar a sintaxe do javascript.

1. Abra o .vimrc e adicione o plugin antes de "call vundle#end()"

```vim
Plugin 'pangloss/vim-javascript'
```

2. Abra o Vim

```shell
vim
```

3. Execute o comando

```vim
:PluginInstall
```

4. Agora é so sair

```vim
:q
```

Pronto, já temos o nosso plugin instalado. Voce pode instalar quantos plugins quiser, mas quanto mais plugins voce tiver, seu Vim pode começar a ficar lento.

<blockquote><a href="../referencias/fontes-recomendacoes.md">Fontes e Recomendações</a><blockquote>