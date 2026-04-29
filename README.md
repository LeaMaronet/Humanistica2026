# Une chaîne de traitement pour l'analyse iconographique de bas-reliefs indiens anciens : segmentation, clusterisation et catégorisation multimodale

Léa Maronet

Ce dépôt GitHub contient le code associé au poster présenté lors de l’atelier Distam de la conférence [Humanistica 2026](https://humanistica2026.sciencesconf.org/), qui s’est tenu à EPITA (Paris) le 18 mai 2026.

Ce poster présente, sous la forme d’une étude de cas, la chaîne de traitement développée dans le cadre d’une [thèse de doctorat](https://theses.fr/s370977) consacrée à l’analyse iconographique d’un groupe de motifs en bas-relief, fréquemment représentés en Inde ancienne (III<sup>e</sup> siècle av. n. è. – III<sup>e</sup> siècle ap. n. è.).
Il propose une méthodologie de traitement computationnelle visant à répondre à la problématique de la mise à l’échelle de l’analyse iconographique, en cherchant à concilier le traitement automatique de corpus visuels de grande taille avec le maintien d’un niveau de finesse analytique compatible avec l’interprétation des motifs.

Les notebooks doivent être exécutés dans l'ordre : 
1. ExtractionMasques.ipynb
2. Clustering.ipyng
3. CategorisationMultimodale.ipynb


## Architecture du dépôt

```
[Humanistica2026]/
│
├── 📂 data/                                #Contient les données du projet
│   ├── 📂 images/                          #Contient quelques exemples d'images traitées, parmi celles libre de droit  
│   ├── 📂 masques/                         #Contient les motifs extraits des images
│   ├── 📊 corpusTropy.csv                  #Base de données initiales avec les métadonnées des images
│   └── 📊 polygonesMasques.csv             #Coordoonées des motifs obtenus avec YOLOv11 fine-tuné
│
├── 📂 notebooks/                           #Contient l'ensemble des notebooks de traitement
│   ├── 💻 ExtractionMasques.ipynb          #Notebook pour l'extraction des motifs segmentés
│   ├── 💻 Clustering.ipynb                 #Notebook pour la clusterisation des motifs
│   └── 💻 CategorisationMultimodale.ipynb  #Notebook pour la catégorisation automatique des motifs
│
├── 📂 outputs/                             #Contient l'ensemble des sorties post-traitement
│   ├── 📂 clustering/                      #Contient les sorties da la clusterisation 
│   ├── 📂 categorisation/                  #Contient les sorties de la catégorisation automatique
│   ├── 📊 corpusFinal.csv                  #Base de données finale avec la description affinée des motifs
│   ├── 📊 corpusMasques.csv                #Base de données intermédiaire organisée par motifs avec leurs métadonnées
│   └── 📊 corpusMasquesClusters.csv        #Base de données intermédiaire avec les clusters
│
├── poster.pdf        
└── README.md
```

---
# A Processing Pipeline for the Iconographic Analysis of Ancient Indian Bas-Reliefs: Segmentation, Clustering, and Multimodal Categorization

Léa Maronet 

This GitHub repository contains the code associated with the poster presented at the Distam workshop of the [Humanistica 2026](https://humanistica2026.sciencesconf.org/) conference, held at EPITA (Paris) on May 18, 2026.

The poster introduces, as a case study, a processing pipeline developed during a [PhD project](https://theses.fr/s370977) focused on the iconographic analysis of a group of bas-relief motifs frequently depicted in ancient India (3<sup>rd</sup> century BCE – 3<sup>rd</sup> century CE).
It proposes a computational methodology addressing the challenge of scaling iconographic analysis, namely how to automatically process large visual corpora while preserving the level of analytical granularity required for meaningful motif interpretation.

The notebooks must be executed in the following order:
1. ExtractionMasques.ipynb
2. Clustering.ipyng
3. CategorisationMultimodale.ipynb

## Structure of the repository

```
[Humanistica2026]/
│
├── 📂 data/                                #Contains the project data
│   ├── 📂 images/                          #Contains sample processed images, among those that are free of use 
│   ├── 📂 masques/                         #Contains motifs extracted from images
│   ├── 📊 corpusTropy.csv                  #Initial database with image metadata
│   └── 📊 polygonesMasques.csv             #Coordinates of motifs obtained using fine-tuned YOLOv11
│
├── 📂 notebooks/                           #Contains all processing notebooks
│   ├── 💻 ExtractionMasques.ipynb          #Notebook for extracting segmented motifs
│   ├── 💻 Clustering.ipynb                 #Notebook for motif clustering
│   └── 💻 CategorisationMultimodale.ipynb  #Notebook for automatic motif categorization
│
├── 📂 outputs/                             #Contains all post-processing outputs
│   ├── 📂 clustering/                      #Contains clustering outputs
│   ├── 📂 categorisation/                  #Contains outputs from automatic categorization
│   ├── 📊 corpusFinal.csv                  #Final database with refined motif descriptions
│   ├── 📊 corpusMasques.csv                #Intermediate database organized by motifs with their metadata
│   └── 📊 corpusMasquesClusters.csv        #Intermediate database with clusters
│ 
├── poster.pdf        
└── README.md

```
