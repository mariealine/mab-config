# MEMENTO-CLI

### GIT

- ajouter tous les fichiers au tracking
`git add .`

- ajouter un fichier au tracking
`git add le_fichier`

- commiter le/les fichiers trackés
`gc -m "nom du commit"`

- pusher en remote
`ggpush`
`git push origin`

- récupère les branches du projet  
`git fetch`

- affiche toutes branches du projet  
`git branch -a`

- switch sur une autre branche  
`gco autre_branche`

- création d'une branche à partir de la courante  
`gco -b nouvelle_branche`

- supprimer une branch remote  
`git push origin :nom_de_la_branche`

- supprimer une branche locale  
`git branch -D nom_de_la_branche`

- sauvegarde temporaire des mofification  
`git stash`

- application des modifiactions temporaire  
`git stash apply`

### Ghost

- lancer le projet - en dev (folder : ghost - pas themes)
- `grunt dev`

- compilation des fichiers de style Ghost
- `grunt build `

### OTHERS

- fetch des locales / localeapp
`localeapp pull`

- Optimisation des SVG  
`svgo --disable=removeUnknownsAndDefaults path/de/limage.svg`
