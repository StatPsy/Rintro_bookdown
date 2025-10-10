Ce bookdown a pour but d'être un guide R pour les étudiants de statistique I.

## Bookdown

Il se base sur la structure du book mis par défault sur R Markdown et le package bookdown (https://github.com/rstudio/bookdown). 

Il est nécessaire d'installer le package bookdown pour utiliser cette extension dans R.

```{r}
# stable version on CRAN
install.packages("bookdown")
```

Les instructions suivantes partent du principe que vous avez des connaissances de git et detaillent la procedure pour GitHub Desktop:

1. Pullez le repo en ligne avant de commencer à travailler.
1. Créez une branche basée sur `main` avec un nom explicit court (e.g. updated_chap1)
1. Une fois les modifications réalisées dans Rstudio, construisez le livre avec la commande `bookdown::render_book("index.Rmd", "bookdown::gitbook")`
1. **Dans Rstudio n'utilisez pas `knit`pour voir vos changements**, à la place naviguez vers `index.html` (ici par exemple: `/Users/moi/Documents/GitHub/Rintro_bookdown/docs/index.html`) et double-cliquez
1. Dans github desktop de nouveau: Sélectionnez les modifications que vous désirez mettre sur GitHub
1. Ajoutez un message clair puis vous pouvez `commit` les modifications
1. Pour mettre vos modifications sur github, publiez votre branche.
1. Naviguez vers le repo sur GitHub (https://github.com/StatPsy/Rintro_bookdown/)
1. Cliquez sur Compare and pull request (bandeau jaune)
1. **important** Changez le `base repository` pour `main`dans StatPsy en vérifiant bien que vous ne pointez pas vers le bookdown original chez meganebollen/meganebollen.github.io
1. decrivez les changements puis creer le pull request
1. assignez un membre du repo comme reviewer et attendez l'évaluation avant l'intégration
