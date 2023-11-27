# R Markdown Project Template

This template gives you a starting point for structuring a datascience project using R markdown. Clone this repo and knit [Main.Rmd](Main.Rmd) to get started.

Having chapters in separate files facilitates collaboration and version control. Also, each chapter imports the same [Knitr_setup.Rmd](Knitr_setup.Rmd) file, so you can knit individual chapters or the main document [Main.Rmd](Main.Rmd) with the same settings. Make sure you can knit your chapter independently, because knitting your main document will become slower as your project grows.

In the [Data_prepartion.Rmd](Data_preparation.Rmd) chapter, you may prepare your data an save it e.g. as a .csv file. In your following chapters, you can load the data from the .csv file.

The template renders html files, but it's easy to change it to pdf.
