# status
Dans Github, le statut (status en anglais) est une fonctionnalité qui permet de savoir si une intégration ou une construction de code a réussi ou échoué.
En résumé, le statut dans Github est une fonctionnalité utile pour suivre l'état des intégrations et des constructions de code, ce qui permet aux développeurs de détecter rapidement les problèmes et de les corriger avant qu'ils ne deviennent des problèmes plus graves pour le projet.
# clone
`git clone` permet de récupérer un dépôt Git distant et de l'avoir localement. Par exemple, `git clone git@github.com:CIN-A/CIN-A.git` va chercher le dépôt https://github.com/CIN-A/CIN-A et crée un dossier `CIN-A` avec son contenu.
# push
# pull/fetch
# merge
# rebase
# reset
`Git reset` est utilisé pour mettre à jour la branche actuelle.
Il peut également être utile de restaurer l’index, en intersection avec git restore.
Pour réinitialiser l’index et le répertoire de travail à l’état du dernier commit, la commande git reset est utilisée :
`git reset --hard HEAD`
# branch
Une branche permet de travailler sur une fonctionnalité sans risquer de corrompre les fonctionnalités fonctionnelles.
git branch                        -> Donne la liste des branches du répo
git branch Nouvelle branch        -> Crée une branch avec le nom "Nouvelle branch"
# checkout
sert à changer de branche 
git checkout ＜nom de la branche＞

l'argument -b permet de crée la branche et de automatiquement switch dessu en se basant sur la branche ou on se situe au moment de la commande
git checkout -b ＜nouvelle-branche＞

on peut préciser sur quelle branche on se base
git checkout -b ＜nouvelle-branche＞ ＜branche-existante＞

# log
# commit
