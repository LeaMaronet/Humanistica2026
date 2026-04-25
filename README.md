# Une chaîne de traitement pour l'analyse iconographique de bas-reliefs indiens anciens : segmentation, clusterisation et catégorisation multimodale

Léa Maronet

Ce dépôt GitHub contient le code associé au poster présenté lors de l’atelier Distam de la conférence [Humanistica 2026](https://humanistica2026.sciencesconf.org/), qui s’est tenu à EPITA (Paris) le 18 mai 2026.

Ce poster présente, sous la forme d’une étude de cas, la chaîne de traitement développée dans le cadre d’une [thèse de doctorat](https://theses.fr/s370977) consacrée à l’analyse iconographique d’un groupe de motifs en bas-relief, fréquemment représentés en Inde ancienne (III<sup>e</sup> siècle av. n. è. – III<sup>e</sup> siècle ap. n. è.).
Il propose une méthodologie de traitement computationnelle visant à répondre à la problématique de la mise à l’échelle de l’analyse iconographique, en cherchant à concilier le traitement automatique de corpus visuels de grande taille avec le maintien d’un niveau de finesse analytique compatible avec l’interprétation des motifs.


## Architecture du dépôt

```
[Humanistica2026]/
│
├── 📂 data/            #Contient les données du projet
│   └── 📂 images/      #Contient quelques exemples d'images traitées, parmi celles libre de droit      
│
├── 📂 notebooks/       #Contient l'ensemble des notebooks de traitement
│
├── 📂 outputs/         #Continent l'ensemble des sorties post-traitement
│   ├── 📂 clustering   #Sorties du clustering  
│   └── 📂 labeling     #Sortie de la catégorisation automatique
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

## Structure of the repository

```
[Humanistica2026]/
│
├── 📂 data/            # Contains project data
│   └── 📂 images/      # Contains a selection of processed images (limited to those with open access rights)
│
├── 📂 notebooks/       # Contains all processing notebooks
│
├── 📂 outputs/         # Contains all post-processing outputs
│   ├── 📂 clustering   # Clustering outputs  
│   └── 📂 labeling     # Automatic labeling outputs
│
├── poster.pdf        
└── README.md
```
