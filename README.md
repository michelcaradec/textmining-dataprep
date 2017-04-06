# textmining-prepare

Data preparation for [textmining](https://github.com/michelcaradec/textmining) Python package.

## First names

### Data source

[Fichier des prénoms - Edition 2016](http://www.data.gouv.fr/fr/datasets/fichier-des-prenoms-edition-2016/), published by [INSEE](https://www.insee.fr/).

File used: [Fichier par départements de naissance](https://www.insee.fr/fr/statistiques/fichier/2540004/dpt2015_txt.zip)

### Transformations

Data preparation is done using **pyspark** on an Apache Spark cluster.

See [firstnames.ipynb](https://github.com/michelcaradec/textmining-dataprep/blob/master/firstnames.ipynb) Jupyter notebook.
