# SCADR End of life care project

End of life care analyses with SCADR at Edinburgh Napier University. This project has been running since 2015, and several analysts have worked on it. Extensive documentation is available in a dropbox folder, most notably a file called `01-Introduction to the Project.docx`. This repository contains some additional scripts I've written to support the analysis.


# Contents

* [`producing_tables_for_migrations_paper.Rmd`](./producing_tables_for_migrations_paper.Rmd) - in this script descriptives for all terms used in the logistic regression models exported from the project safe haven are compiled - the exported file is an excel spreadsheet with various SPSS output tables, including logistic regression outputs, some of which include frequency tables of the various explanatory variables. This script pulls the frequencies from the spreadsheets and compiles them into a `.csv` file. I've since been able to recompile & export the same table from the safe haven so this hacky approach isn't needed.

* [`eol_care_migrations_presentation.Rmd`](./eol_care_migrations_presentation.Rmd) - Unfinished. This was an attempt at a set of slides using `xaringan`, presenting the end-of-life migrations work within this project.

* [`extract_quebec_icd10_codes.Rmd`](./extract_quebec_icd10_codes.Rmd) - this script extracts the ICD-10 codes used to define palliative care needs in an appendix to the "Quebec" paper [[1]](#1) and compiles them into a `csv` file for use in analysis.


# References

<a id="1">[1]</a>  Bédard, C., Major, D., Ladouceur-Kègle, P., Guertin, M. H., & Brisson, J. (2006). Soins palliatifs de fin de vie au Québec: définition et mesure d’indicateurs. Partie 1. Population adulte (20 ans et plus). Québec, Canada: Institut national de santé publique du Québec.