# Vim

Vous pouvez modifier vim pour avoir :
- Un nombre precis d espace avec Tab
- Afficher le numero des lignes
- Ajouter le header
- ...

## .vimrc

```shell
vim ~/.vimrc
```

### Config

Vous pouvez copier la liste suivante. L'explication de chaque ligne est disponible juste apres.

```vim
" Visuel
set number
syntax on

" Indentation (4 espaces)
set tabstop=4
set shiftwidth=4
set noexpandtab
set autoindent
```

- `set number` : Affiche les numeros de ligne
- `syntax on` : Coloration syntaxique
- `set tabstop` : Definit la largeur visuelle d un tab (ici 4)
- `set shiftwidth=4` : Une indentation vaut 4 colonnes
- `set noexpandtab` : les tabs sont des vrais tabs (et pas des espaces)
- `set autoindent` : indente automatique apres Enter


## Automatiser les commentaires

```shell
mkdir -p ~/.vim/pack/plugins/start
git clone https://github.com/tpope/vim-commentary.git ~/.vim/pack/plugins/start/vim-commentary
```

### Tester que le plugins est installe

```vim
:echo exists(':Commentary')
```

Si tout se passe bien, renvoie 2.

### Usage

- `gcc` : Commente / Decommente la ligne courante
- Mode visuel (`V`), selectionner les lignes puis`gc`