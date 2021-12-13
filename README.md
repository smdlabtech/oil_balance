# Analyse du bilan d'un groupe pétrolier de 1969 à 1984 
Les données étudiées sont issues des bilans annuels d'un groupe pétrolier sur la période 1969 à 1984. 
Les postes du bilan qui suivent chaque année sont bien décrits.

L'étude de ce bilan s'est déroulée en trois étapes :
- Présentation des données --> 
- Statistiques descriptives --> 
- Réalisation d'une ACP (Analyse en Composantes Principales) centrée réduite

# Table of contents
- [installations](#install)
- [presentation of the data](#presentation)
- [descriptive statistics](#descriptive)
- [realization of a PCA](#pca)
- [realization of a PCA](#sponsors)


<h2 id="install">Installations</h2>
Install the following libraries:

```
library(knitr)
library(dplyr)
library(FactoMineR)
```

<h2 id="presentation">Presentation of the data </h2>
Les données étudiées sont issus des bilans annuels d'un groupe pétrolier sur la période
1969 à 1984. Les postes de bilans suivant chaque année sont décrit ci-dessous:
  
  * **_NET_** : Situation nette ; représente l'ensemble des capitaux propres de l'entreprise
  * **_INT_** : Intérêts ; représente l'ensemble des frais financiers supportés par l'entreprise.
  * **_SUB_** : Subventions ; représente le montant total des subventions accordées par l'état.
  * **_LMT_** : Dettes à long et moyen terme.
  * **_DCT_** : Dettes à court terme.
  * **_IMM_** : Immobilisations ; représente l'ensemble des terrains et du matériel de l'entreprise.
  * **_EXP_** : Valeurs d'exploitation.
  * **_VRD_** : Valeurs réalisables et disponibles ; ensemble des créances à court terme de l'entreprise.

Les données sont de nature quantitatives et ont été ventilées en pourcentage par année, la somme des éléments d'une même
ligne vaut 100, de manière à éviter les effets dus à l'inflation.
Et elles se présentent sous la forme suivante:





<h2 id="descriptive">Descriptive statistics</h2>

<h2 id="pca">Realization of a PCA</h2>


<h2 id="sponsors">

Sponsors 🏆

</h2>

> There are no sponsors yet



