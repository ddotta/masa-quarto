# masa-quarto

Une extension [Quarto](https://quarto.org) qui intègre la charte graphique du [Masa](https://agriculture.gouv.fr/) pour réaliser des diaporamas revealjs.

## Pré-requis

Vous pouvez utiliser ce template depuis (au choix) :  

**1. Votre poste en local**   
    -> Dans ce cas, assurez vous d'avoir au minimum la version `v2022.07` de RStudio qui intègre Quarto.

**2. Cerise**  
    -> Pour l'instant, il faut attendre l'arrivée de Cerise v3 pour compiler des documents Quarto.
    
**3. Le SSP Cloud**  
    -> Vous pouvez utiliser au choix un service RStudio ou VS Code qui intègre déjà par défaut Quarto.
   

## Installation

- Vous pouvez clôner ce dépôt gitlab sur votre machine avec l'instruction :  

 ``` bash
 git clone https://forge.agriculture.rie.gouv.fr/gitlab/ssp/bmis/charte-graphique/masa-quarto.git
 ```
 

## Obtenir la présentation

- Avec le terminal :  

``` bash
quarto render mondocument.qmd
```

- Avec RStudio :  

Ouvrir le fichier `.qmd` et cliquer sur le bouton ![](img/render_rstudio.png)

- Avec VS Code :

Installer [l'extension Quarto](https://marketplace.visualstudio.com/items?itemName=quarto.quarto) puis cliquer sur le bouton ![](img/render_rstudio.png)

## Pour aller plus loin

Lire la [documentation Quarto sur le format revealjs](https://quarto.org/docs/presentations/revealjs/)