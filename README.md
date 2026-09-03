# Analyse de données et apprentissage machine : Théorie et mise en œuvre en Python

Ce dépôt contient les ressources officielles, les exemples de code, les figures et les animations liés au livre :

**« Analyse de données et apprentissage machine : Théorie et mise en œuvre en Python »** par [Neila Mezghani](https://www.teluq.ca/siteweb/univ/en/nmezghan.html).

## 📚 Éditions disponibles

### [1ère édition](./1ere-edition/)

<div align="center">
<img src="https://m.media-amazon.com/images/I/61pzu7YO2aL._SL1303_.jpg" alt="Couverture du livre Analyse de données et apprentissage machine" width="300">
</div>

**📚 <a href="https://www.amazon.ca/Analyse-données-apprentissage-machine-Théorie/dp/B0HL14SJ4M" target="_blank">Acheter le livre sur Amazon</a>**

La première édition couvre les principaux concepts de l'analyse de données et de l'apprentissage machine en 16 chapitres :

1. **Concepts fondamentaux en analyse de données et en apprentissage machine**
2. **Préparation et prétraitement des données**
3. **Réduction de la dimension**
4. **Modèles de régression**
5. **Méthodes bayésiennes en apprentissage machine**
6. **Arbres de décision**
7. **La méthode des k plus proches voisins**
8. **Machines à vecteurs de support**
9. **Réseaux de neurones artificiels**
10. **Méthodes ensemblistes**
11. **Interprétabilité et explicabilité des modèles d'apprentissage machine**
12. **Techniques de regroupement**
13. **Règles d'association**
14. **Détection d'anomalies**
15. **Programmation dynamique et méthodes de Monte Carlo**
16. **Apprentissage par différence temporelle**

## 🎯 Contenu du dépôt

- 📓 **Notebooks Jupyter** : exemples pratiques et implémentations pour chaque chapitre
- 🖼️ **Figures et visualisations** : illustrations générées selon les conventions graphiques du livre
- 🎬 **Animations pédagogiques** : visualisations dynamiques de certains algorithmes
- 📊 **Données d'exemple** : jeux de données nécessaires aux simulations
- 🔬 **Résultats d'expériences** : résultats de référence et métriques de performance

## 🚀 Démarrage rapide

### Prérequis

- Anaconda ou Miniconda
- Le fichier `1ere-edition/environment.yml`
- Une connexion Internet pour le premier téléchargement de certaines données

Si Conda n’est pas installé, installez d’abord Miniconda ou Anaconda.

### Installation

1. Clonez ce dépôt :

   ```bash
   git clone https://github.com/BiomedicalDataMining/analyse-donnees-apprentissage-machine.git LivreAM-Simulations-VF
   cd LivreAM-Simulations-VF
   ```

2. Créez l'environnement de la première édition :

   ```bash
   conda env create -f "1ere-edition/environment.yml"
   ```

3. Activez l'environnement :

   ```bash
   conda activate livre_am_ed1_py312
   ```

4. Lancez JupyterLab :

   ```bash
   jupyter lab
   ```

5. Ouvrez le dossier `1ere-edition`, puis le notebook du chapitre souhaité.

## 📁 Organisation des chapitres du livre

```text
LivreAM-Simulations-VF/
├── .gitignore
├── README.md
└── 1ere-edition/
    ├── environment.yml
    ├── README.md
    ├── Chapitre 01 - Concepts fondamentaux/
    ├── Chapitre 02 - Préparation des données/
    ├── Chapitre 03 - Réduction de la dimension/
    ├── Chapitre 04 - Modèles de régression/
    ├── Chapitre 05 - Méthodes bayésiennes/
    ├── Chapitre 06 - Arbres de décision/
    ├── Chapitre 07 - K-plus proches voisins/
    ├── Chapitre 08 - Machines à vecteurs de support (SVM)/
    ├── Chapitre 09 - Réseaux de neurones/
    ├── Chapitre 10 - Méthodes ensemblistes/
    ├── Chapitre 11 - Interprétabilité et explicabilité/
    ├── Chapitre 12 - Méthodes de regroupement/
    ├── Chapitre 13 - Règles d'association/
    ├── Chapitre 14 - Détection d'anomalies/
    ├── Chapitre 15 - Programmation dynamique et Monte-Carlo/
    └── Chapitre 16 - Différence temporelle/
```

Chaque dossier de chapitre contient son notebook et, selon le cas, des sous-dossiers `data` et `Figures`.

Chaque chapitre contient, selon les besoins :

- 📓 **Notebook Jupyter** avec le code présenté dans le livre
- 🖼️ **Figures** aux formats PNG, GIF ou PDF
- 📊 **Données d'exemple** nécessaires aux simulations
- 🎬 **Animations** pour certains chapitres

## 🛠️ Technologies utilisées

- **Python 3.12** : langage principal
- **NumPy et pandas** : calcul numérique et manipulation des données
- **Matplotlib et Seaborn** : visualisation
- **SciPy et scikit-learn** : méthodes statistiques et apprentissage machine
- **TensorFlow/Keras** : réseaux de neurones
- **JupyterLab** : environnement interactif

## 📖 Comment utiliser ce dépôt

1. **Étudiant·e·s** : suivez les chapitres dans l'ordre, exécutez les notebooks et expérimentez avec les paramètres.
2. **Enseignant·e·s** : utilisez les figures, animations et exemples dans vos cours.
3. **Praticien·ne·s** : consultez les implémentations comme point de départ pour vos projets.

## 📌 Auteure

**[Neila Mezghani](https://www.teluq.ca/siteweb/univ/en/nmezghan.html)**

- Professeure à l'Université TÉLUQ
- Spécialiste en apprentissage automatique et en intelligence artificielle
- [LinkedIn](https://ca.linkedin.com/in/neila-mezghani)

## 📞 Support

Pour toute question ou tout problème :

- Ouvrez une [issue sur GitHub](https://github.com/BiomedicalDataMining/analyse-donnees-apprentissage-machine/issues)
- Consultez le README de la première édition
- Référez-vous au livre pour les explications théoriques détaillées

## 📄 Droits d'auteur

Copyright © 2026 Neila Mezghani. Tous droits réservés.

---

⭐ **N'hésitez pas à donner une étoile au projet si vous le trouvez utile !**
