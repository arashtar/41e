# Historique des commandes du TP1

### Creation d'un depot

> - Initialise un depot vide, cette commande est execute une seule fois
> - Si on l'execute une deuxieme fois on detruit le depot
- `git init`

---

### Récupérer localement sur VSC un dépôt sur Github

- `git pull https://github.com/eddytuto/41e.git main `
---


### Verifier le statut 
- `git status` 
---
### Afficher l'historique des commits
- `git log`
- `git log --oneline`
---
### Naviguer dans les branches
- pour changer le nom d'une branche 
    - `git branch -m main` //change le nom de la branche courante pour main
- Pour creer une nouvelle branche 
    - `git branch aa_entete`
- Pour changer de branch
    - `git checkout main`
    - On ne peut pas changer de branche si la branche courante n'a pas ete <<commit>> valider
    - `git checkout << id du commit >>`
    - `git checkout << étiquette du commit >>`
 ###  Pour creer une etiquete
    - `git tag v1.0.0 ` //creation de l'etiquete v1.0.0
    -   `git tag` //  permet d'afficher l'ensembe des tag (etiquette)
    - `git checkout v1.0.0 `// Pour se deplacer dans le commit v1.0.0 (deplace le pointeur <<head>>)

    ---
### serveur distant
- Pour definir un alias identifiant le serveur disteant 
    - `git remote add 41e https://github.com/arashtar/41e.git`
    - `git remote -v` //permet voire la list des alias de serveur distant
    - `git push 41e main` // pousser mon dernier commit vers la branch main du depot distant 41e
  ---
### Serveur distant
- Pour definir un alias identifiant le serveur disteant 
    - `git remote add 41e https://github.com/arashtar/41e.git`
    - `git remote -v` //permet voire la list des alias de serveur distant
    - `git push 41e main` // pousser mon dernier commit vers la branch main du depot distant 41e
 ---
    

-`https://github.com/arashtar/41e.git`

-`git remote -v`

- `git log --oneline`

### pousser vers le github

- `git push 41e main `
---

### Création du fichier .gitignore à la racine
- ` Ajout de syle.css et style.css.map dans le fichier`
---
### Faites quelques changements dans le fichier et envoyez-le à Github

-  ` git add --all`
- ` git commit -m "ajout d'un fichier<<gitignore>>`
- ` Ajout de <h1> titre<h1> en html`
-  ` git add --all`
- ` git commit -m "ajout d'un <h1> titre<h1>`
- `git checkout main`
- `git push 41e main`
- `git checkout aa_entete`
- `git push 41e aa_entete`

