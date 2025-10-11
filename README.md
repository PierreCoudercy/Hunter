# Installation
## Windows

Afin de récuperer les données et de pouvoir les éditers de façon sur sans écraser et détruire les travailles de autres personnes exploitant les notes présente ici, il faut utiliser un minimum le système GIT.

Pour utiliser GIT sous windows, il suffit de se rendre sur la page de Git :

https://git-scm.com/downloads/win

Et de télécharger le paquet : *Git for Windows/x64 Setup*
Il faut ensuite installer le paquet en suivant les instructions du wizard d'installation, je vous invite à installer l'invit de commande Git Bash pour windows afin de simplifier l'utilisation.

Une fois l'installation terminée ouvrir votre menu démarré et chercher l'application Git Bash, afin de la lancer.
Dans la console maintenant ouverte (n'ayant pas peur je vais vous indiquer les commandes nécessaire).
Nous allons dans ce terminal importer le dépôt, puis créer une banche pour vos notes qui pourra plus facilement être fusionnée avec les restes des notes, tapez les commandes suivante en remplaçant <votre_nom> par un identifiant de votre choix qui permettra de distinguer le travail des uns et des autres:
```
cd /chemin/ou/vous/souhaitez/stocker/vos/notes
git clone https://github.com/PierreCoudercy/Hunter.git
git checkout -b <votre_nom>
git push
git config set credential.helper manager
```
Dans le terminal au bout de la ligne vide il devrait y avoir <votre_nom> entre parenthèses.
Dans Obsidian ouvrez le dossier comme vos autres dossiers et vérifier que la valeur <votre_nom> apparaît bien en bas à droite de l'interface sinon cliquez sur cette dernière et sélectionnez la branch avec <votre_nom>.

## Linux

Git est déjà installé sur la plus part des systèmes linux, il suffit donc d'ouvrir un terminal et de taper les commandes suivante :
```
cd /chemin/ou/vous/souhaitez/stocker/vos/notes
git clone git@github.com:PierreCoudercy/Hunter.git
git checkout -b <votre_nom>
git push

```
# How to use
Une fois que vous avez pris des notes vous allez vouloir les pousser sur le repôt distant. Pour ce faire pas besoin de passer par une autre interface tous se passe dans Obsidian.
Il faut ouvrir le panneau Git d'obsidian afin de dévoiler la liste des fichiers qui ont été modifié lors de votre édition :

![Interface Git d'Obsidian](https://raw.githubusercontent.com/Vinzent03/obsidian-git/master/images/source-view.png)

Au niveau du menu "Changed" cliquez sur le "+" la liste des fichiers en dessous de ce menu doit disparaître et passer dans le menu du dessus
Dans le champ texte qui contient par défaut "vault backup: {{date}}" vous pouvez indiquer le message avec lequel vous souhaitez enregistrer vos fichier
Vous pouvez cliquer ensuite sur l'icône validation tous en haut la seconde icône en partant de la gauche puis sur l'icône courrier sortant la cinquième en partant de la gauche.
Un mot de passe vous sera peut-être demandé.



Pour toute question n'hésitez pas à contacter votre administrateur.
