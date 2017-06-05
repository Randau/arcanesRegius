# Guide d'utilisation

## installation en local

1. ouvrir le terminal
2. naviguer sur ton ordi grâce à `cd` (par exemple `cd projet/` me permet de me placer dans mon dossier projet)
3. une fois l'emplacement choisi faire un `git clone -lien url du repo à cloner-`
4. faire un `cd` pour rentrer dans ce nouveau clone

## travailler en local

1. utiliser le terminal avec la commande `cd` pour aller sur ton projet
2. faire un `git pull` pour récupérer tout ce qui aurait pu être fait
3. travailler sur atom
4. à chaque "block" de travail, ajouter grace à `add -le nom de ton fichier-`
5. faire un `commit` grace `git commit -m "message court d'explication du commit"`
6. `git pull` pour envoyer sur github

## notion de branch

Nous avons deux branches principales, `master` et `gh-pages`.  

Tu peux switcher de l'une à l'autre en utilisant `git checkout -nom de la branche-`

Admettons nous voulons bosser sur le responsive

1. on va sur la branch `master`
2. on crée une branch "responsive" à partir de `master`
3. on fait un `git checkout -nom de la branch-` pour aller sur cette branch puis on travaille en local comme d'habitude
4. une fois que tout est prêt, tu fais un `pull request` sur master (via github c'est plus simple)
5. je viens derrière valider le code, tester, commenté, ect
6. on merge (donc on fusionne)
7. puis lorsqu'on decide que tout est bon dans `master` on envoie ça sur `gh-pages

et HOP ça fait des chocapics
