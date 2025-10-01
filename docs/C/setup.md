# C

## Norminette

La norminette est une commande qui permet de verifier la syntaxe d'un fichier.

Par exemple :

```c
/* NON VALIDE */
int main() {
    return (0); }

/* VALIDE */
int main()
{
    return (0);
}
```

> ⚠️ Si votre projet ne respecte pas a **100%** la norminette, votre projet sera **failed**.
Pensez a la lancer avant de soumettre votre projet a review.

### Lancer la norminette

La norminette est installee par defaut. Pour l'executer, faites :

```
norminette
```

Elle agira dans le dossier en cours.

La norminette contient de l'aide accessible via `norminette -h`.

> ⚠️ Parfois l'enonce vous demanderea d'utiliser des flags (options), comme par exemple `norminette -R CheckForbiddenSourceHeader`