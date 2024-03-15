# Projet_Ai_BigData_Clustering
[French] Projet de Clustering de données   
[English] Data Clustering Project (First it will be the French README then the English README After)  

<div align="center">
  <img width="579" alt="image" src="https://github.com/D-TheProgrammer/Projet_Ai_BigData_Clustering/assets/151149998/e3e1bc46-c4f0-4b71-82bc-cdd172eeb4c9">
</div>

#### SOMMAIRE / SUMMARY
- [Présentation en francais / Presentation in French](#presentation_francais)
- Présentation en anglais / Presentation in English
- Tuoriel dans les deux langues / Tutorial in both languages

## [PRESENTATION EN FRANCAIS](#presentation_francais)

Project par D-TheProgrammer

Le projet sur lequel j'ai travaillé s'appelle `cluster.py` et utilise les fichiers `iris_label.csv` (pour leur type) et `iris_data.csv`(pour leur coordonées) pour traiter les données, notamment en effectuant du clustering et en changeant la couleur des points (représentant des fleurs) en fonction de leur proximité avec un centre. Il est important de noter que les données de ces fleurs, nommées Iris, sont en quatre dimensions  ce qui signifie qu'elles ont quatre caractéristiques par fleur. Cependant, sur le graphique, elles sont représentées en deux dimensions, ce qui peut donner un résultat visuel particulier.

Dans ce projet, le terminal affiche tous les choix possibles parmi plusieurs options. En fonction de ces choix, différents calculs pourront être effectués.

Il est à noter que l'affichage graphique se réalise uniquement à la fin du programme et que plusieurs pages se lanceront simultanément. Chacune d'entre elles comporte des légendes pour se différencier et faciliter la compréhension.

> [!TIP]
> Pour lancer le fichier Python
> ```bash
> python3 clusters.py
> ````


## [ENGLISH PRESENTATION]

Project made by D-TheProgrammer

The project I worked on is called `cluster.py` and uses the files `iris_label.csv` (for their type) and `iris_data.csv` (for their coordinates) to process the data, notably by performing clustering and changing the color of the points (representing flowers) depending on their proximity to a center. It is important to note that the data for these flowers, named Iris, are four-dimensional which means they have four characteristics per flower. However, on the graph they are represented in two dimensions, which can give a particular visual result.

In this project, the terminal displays all possible choices among several options. Depending on these choices, different calculations can be carried out.

Please note that the graphic display is only carried out at the end of the program and that several pages will be launched simultaneously. Each of them has legends to differentiate them and facilitate understanding.

> [!TIP]
> To start the python file
> ```bash
> python3 clusters.py
> ````


## [Tutoriel / Tutorial]

#### ÉTAPE 1 : Choix du nombre de clusters / STEP 1: Choice of the number of Clusters 

<div align="center">
  <img width="638" alt="image" src="https://github.com/D-TheProgrammer/Projet_Ai_BigData_Clustering/assets/151149998/a17e8ba9-dfe5-4c01-9183-44981586201c">
</div>

#### ÉTAPE 2 : Choix des types de centres / STEP 2: Choice of the type of centers
[FRENCH] Le choix '1' consiste à créer des centres de manière aléatoire avec des coordonnées aléatoires, tandis que le choix '0' sélectionnera des fleurs comme centres.  
[ENGLISH] Choice '1' will involve randomly creating centers with random coordinates, while Choice '0' will select flowers as centers.

<div align="center">
  <img width="561" alt="image" src="https://github.com/D-TheProgrammer/Projet_Ai_BigData_Clustering/assets/151149998/c257904c-c6a0-41e8-a9cd-c12b6bc81461">
</div>


[FRENCH] Les centres choisis ou créés sont affichés.  
[ENGLISH] The chosen or created centers are displayed.  
<div align="center">
  <img width="503" alt="image" src="https://github.com/D-TheProgrammer/Projet_Ai_BigData_Clustering/assets/151149998/475bbfbd-525e-46a6-97bf-69477a396324">
</div>


#### ÉTAPE 3 : Choix du calcul des distances (3 méthodes) / STEP 3: Choice of distance calculation (3 methods)

[FRENCH] Le choix du calcul des distances permettra d'attribuer les fleurs aux bons clusters. Si l'utilisateur choisit le calcul de Minkowski (Choix 3), il devra choisir la puissance 'P'.  

[ENGLISH] The choice of distance calculation will allow assigning the flowers to the correct clusters. If the user chooses the Minkowski calculation (Choice 3), they will have to choose the power 'P'.

<div align="center">
<img width="281" alt="image" src="https://github.com/D-TheProgrammer/Projet_Ai_BigData_Clustering/assets/151149998/827cdca5-415d-4873-9e09-ed425378699d">
</div>

[FRENCH] Après cela, les centres sont recalculés pour qu'ils soient au milieu du cluster en termes géographiques   
[ENGLISH] After that, the centers are recalculated so that they are in the middle of the cluster in geographical terms  
<div align="center">
  <img width="493" alt="image" src="https://github.com/D-TheProgrammer/Projet_Ai_BigData_Clustering/assets/151149998/859c6f88-3360-454e-93b5-983573c571a6">
</div>

#### ÉTAPE 4 : SSE et Arrangement du cluster / STEP 4: SSE and Cluster Arrangement

[Français] Le SSE du cluster est affiché avec le nombre de fleurs par type, et enfin le nombre de fleurs total dans le cluster est affiché  
[French] The SSE of the cluster is displayed along with the number of flowers per flower type, and finally the total number of flowers in the cluster is shown  

<div align="center">
  <img width="480" alt="image" src="https://github.com/D-TheProgrammer/Projet_Ai_BigData_Clustering/assets/151149998/5197f3b4-4e64-4a90-ac0f-1629b52f6252">
</div>

#### ÉTAPE 5 : Pureté du cluster / STEP 5: Cluster Purity
<div align="center">
  <img width="364" alt="image" src="https://github.com/D-TheProgrammer/Projet_Ai_BigData_Clustering/assets/151149998/1a37d5a6-3340-4584-85a2-c59614f617a4">
</div>

#### ÉTAPE 6 : Linkage et choix du niveau de coupe pour la fusion des clusters / STEP 5: Linkage and choice of the cutting level for cluster fusion
<div align="center">
  <img width="692" alt="image" src="https://github.com/D-TheProgrammer/Projet_Ai_BigData_Clustering/assets/151149998/e4dbc886-dae4-4325-80d4-5014874f8c3a">
</div>

#### ÉTAPE 6 : Choix de la méthode de linkage (4 méthodes)  / STEP 5: Choice of linking method (4 methods)

[FRANÇAIS] Le programme affichera le nombre de clusters que vous avez choisi initialement et vous demandera combien de clusters vous souhaitez réduire, avec un minimum de 1 (ce qui signifie que toutes les fleurs seront dans le même cluster). Il indiquera également quels clusters seront fusionnés selon la méthode choisie  

[ANGLAIS] The program will display the number of clusters you initially chose and ask you how many clusters you want to reduce to, with a minimum of 1 (meaning all flowers will be in the same cluster). It will also indicate which clusters will be merged with which according to the chosen method  

<div align="center">
<img width="528" alt="image" src="https://github.com/D-TheProgrammer/Projet_Ai_BigData_Clustering/assets/151149998/6146434c-b7cb-4d4b-904e-babc408b3d2b">
</div>

#### ÉTAPE 7 : Retour sur une analyse SSE plus appronfondis  / STEP 7: More in-depth SSE analysis

<div align="center">
<img width="494" alt="image" src="https://github.com/D-TheProgrammer/Projet_Ai_BigData_Clustering/assets/151149998/38231cec-e493-4ddd-b10f-8af7a0f39edf">
</div>


#### ÉTAPE 8 : Enfin, les résultats sont affichés graphiquement (avec 4 fenêtres différentes pour les 4 analyses) / STEP 8: Finally, the results are displayed graphically (with 4 different windows because of the 4 analysis)

<div align="center">
  <img width="579" alt="image" src="https://github.com/D-TheProgrammer/Projet_Ai_BigData_Clustering/assets/151149998/e3e1bc46-c4f0-4b71-82bc-cdd172eeb4c9">
</div>

[Cluster Fusion]
<div align="center">
  <img width="608" alt="image" src="https://github.com/D-TheProgrammer/Projet_Ai_BigData_Clustering/assets/151149998/c670f0ac-b64e-4068-90cc-554de2a310de">
</div>

[SSE]
<div align="center">
  <img width="386" alt="image" src="https://github.com/D-TheProgrammer/Projet_Ai_BigData_Clustering/assets/151149998/c83263bc-5a05-41d3-b659-297d158eb571">
</div>
