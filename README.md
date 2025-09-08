Ce bookdown a pour but d'être un guide R pour les étudiants de statistique I.

## Bookdown

Il se base sur la structure du book mis par défault sur R Markdown et le package bookdown (https://github.com/rstudio/bookdown). 

Il est nécessaire d'installer le package bookdown pour utiliser cette extension dans R.

```{r}
# stable version on CRAN
install.packages("bookdown")
```

1. Pull le repo en ligne avant de commencer à travailler.
1. Crééz une branche basée sur `main`avec un nom explicit court (e.g. updated_chap1)
1. Une fois les modifications réalisées, construisez le livre avec la commande `bookdown::render_book("index.Rmd", "bookdown::gitbook")`
1. Sélectionnez les modifications que vous désirez mettre sur le github avec `stage`
1. Ajoutez un message clair puis vous pouvez `commit` les modifications
1. Pour mettre vos modifications sur github, réalisez un `push` de vos commits.
