# Command line and linux commands

## Global

## Le terminal 

L'OS que nous utiliser est Fedora Linux.
Il comporte des differences avec MacOS et Windows.

> Le terminal correspond a un invite de commande qui permet de lancer un shell.

Vous allez devoir manipuler le terminal pour effectuer differentes actions.
Par exemple :

- Creer une clee SSH pour lier votre compte 42 a votre compte GitHub et rejoindre l'organisation 42.
- Creer, supprimer, renommer, deplacer et  afficher des fichiers depuis la ligne de commande.
- Ecrire votre code sur un editeur de fichier (vim ou emacs).
- Gerer votre projet via git
- ...

Par defaut vous avez differents terminaux :

- terminal
- fish
- terminator

Globalement ils font la meme chose, mais on des subtilites, a vous de trouver le votre.

## Quelques commandes importantes

```shell
pwd # permet de connaitre le repertoire actuel. 
ls # Affiche les elements du repertoire courant
mkdir # Creer un dossier
touch # Creer un fichier
cat # Affiche le contenu d'un fichier
rm # Supprimer un dossier ou fichier

## Documentation
man # Affiche le manuel d'une commande
info # Afficher des informations sur une commande
[command] -h # Afficher l'aide d'une commande
```

## Bien utiliser son OS (Linux)

Depuis le terminal, vous pouvez lancer votre explorateur de fichier (Par exemple pour visualiser un PDF).
Sur GNOME, il s'agit de Nautilus.

La commande `nautilus` permet de lancer l'explorateur de fichier.

Par exemple 

```shell
nautilus .
```

permet d'afficher le repertoire courant.

## git et Github

git est un outil qui permet de manager vos projets tech.
Par exemple sauvegarder vos fichiers ou fusionner differents morceaux de code.

Vous devrez gerer votre nom d'utilisateur et email.

Retenez 3 commandes importantes :

- `git add`
- `git commit`
- `git push`

