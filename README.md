# Robust-Red-Blood-Cell-Classification
Classification robuste des globules rouges en conditions réelles avec interprétabilité

# HemoAI: Robust Red Blood Cell Classification

## Contexte

La drépanocytose (sickle cell disease) est une maladie génétique touchant particulièrement les populations d'Afrique centrale et de l’Ouest. Elle se caractérise par la présence de globules rouges falciformes, qui peuvent provoquer de graves complications de santé. Le dépistage précoce et fiable est essentiel, mais dans de nombreux contextes à ressources limitées, la qualité des images de frottis sanguins varie fortement (bruit, éclairage, contraste).

Ce projet combine **imagerie numérique et Machine Learning** pour développer un modèle capable de classifier les globules rouges, y compris les cellules falciformes, de manière robuste et interprétable dans des conditions réelles.

---

## Objectif du projet

- Créer un modèle de classification des globules rouges **robuste aux variations d’image** (bruit, contraste, éclairage, flou).  
- Fournir un modèle **interprétable**, capable de visualiser les zones de l’image qui influencent la décision du modèle.  
- Démontrer la **valeur clinique** d’un tel modèle pour le dépistage automatisé de la drépanocytose.

---

## Données

- Dataset utilisé : images de globules rouges (globules normaux et falciformes).  
- Prétraitement : redimensionnement, normalisation, augmentation pour simuler différentes conditions réelles d’acquisition.  
- Organisation des données :  
