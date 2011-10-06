VimMyConf
=========

My vim configuration, based on the config shared by [karlosgliberal](https://github.com/karlosgliberal/VimMyConf)

It's managed with [pathogen](http://www.vim.org/scripts/script.php?script_id=2332)


Installation
---------

1. Backup of your vim configuration 

        mv ~/.vim ~/.vimold

2. Clone repo

        git clone git@github.com:penyaskito/VimMyConf.git ~/.vim

3. Create symlinks

        ln -s ~/.vim/vimrc ~/.vimrc

4. Fetch submodules

        cd ~/.vim
        git submodule init
        git submodule update

TODO
====

El plugin snipmate.vim lo añado a bundles desde un fork propio y asi incluyo un php.snippets modificado con las golosinas de drupal
Supuestamente se tendria que poder hacer sin este apaño, pero se tiene que cambiar el filetype a tipo "drupal" y no me gusta.
Mientras que descubro como se usar filetype-overrule se queda así

Plugins
=======

* nerdtree => Gestor de directorios  
* snipmate => Atajos tipo texmate
* sokoban.vim => Juego sokoban
* supertab => Para acceder a la funcion autocompletado con el tabulador igual que los snipet
* tcomment_vim => Comentarios en el codigo
* vim-coffee-script => Coffescript
* vim-colors-solarized 
* vim-fugitive => Gestión de git para vim (BRUATL)
* vim-jade => Sistema de plantillas de expressjs
* vim-jquery => Integración con jquery
* vim-markdown 
* vim-stylus => Css diyievolucionado tipos sass o less (node.js)
