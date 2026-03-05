# Positionnement Initial TSMEL

## Description

Application web de positionnement initial pour la formation **Technicien Supérieur en Méthodes et Exploitation Logistique (TSMEL)**.

Cette application permet d'évaluer les apprenants sur :
- Leurs compétences en **logistique**
- Leurs connaissances en **mathématiques**
- Leur niveau en **bureautique** (Word, Excel)
- Leur niveau d'**anglais professionnel B1**
- Leurs **préférences d'apprentissage** et **besoins d'accompagnement**

## Structure de l'application

### 📁 Fichiers

- **`index.html`** - Page d'accueil avec choix d'interface (Apprenant / Formateur)
- **`questionnaire.html`** - Interface Apprenant (questionnaire complet)
- **`formateur-detail.html`** - Interface Formateur (tableau de bord analytique)

### 🎯 Fonctionnalités

#### Interface Apprenant (`questionnaire.html`)
- ✅ Questionnaire de positionnement en 7 sections
- ✅ Navigation par étapes avec barre de progression
- ✅ Sauvegarde locale des réponses (localStorage)
- ✅ Export des données au format JSON

**Sections :**
1. **Informations Générales** - Nom, date, formateur
2. **Expérience et Situation** - Parcours en logistique
3. **Évaluation Logistique** - 7 compétences métier TSMEL
4. **Mathématiques** - Calculs, volumes, ratios, indicateurs
5. **Bureautique** - Maîtrise Word & Excel
6. **Anglais B1** - Grammaire, vocabulaire, compréhension
7. **Modalités d'Apprentissage** - Style, préférences, besoins

#### Interface Formateur (`formateur-detail.html`)
- 📊 **Tableau de bord analytique**
- 📈 **Graphiques radar et barres** (via Chart.js)
- 🎯 **Scores par domaine** (Logistique, Maths, Bureautique, Anglais)
- 💡 **Synthèse automatique** avec recommandations pédagogiques
- 📄 **Export PDF** et sauvegarde JSON

## 🚀 Utilisation

### Déploiement GitHub Pages

L'application est accessible via GitHub Pages :

```
https://sylgo974-jpg.github.io/Evaluation-initiale/
```

### Utilisation locale

1. Cloner le repository :
```bash
git clone https://github.com/sylgo974-jpg/Evaluation-initiale.git
cd Evaluation-initiale
```

2. Ouvrir `index.html` dans un navigateur

### Flux d'utilisation

1. **Apprenant** : Accède à `questionnaire.html`, remplit le formulaire, enregistre les données
2. **Formateur** : Récupère les données JSON, les charge dans `formateur-detail.html` pour analyser les résultats

## 🔧 Personnalisation

### Remplacer le questionnaire

Pour utiliser le **fichier HTML complet** (`Grille-Positionnement-TSMEL.html`) :

1. Renommer le fichier attaché en `questionnaire.html`
2. Remplacer le fichier existant
3. Supprimer la section "Tableau de Bord" (qui sera uniquement dans `formateur-detail.html`)

###  Adapter l'interface formateur

Dans `formateur-detail.html`, vous pouvez :
- Ajouter des graphiques supplémentaires
- Personnaliser les recommandations pédagogiques
- Modifier les seuils d'évaluation (débutant/intermédiaire/avancé)

## 📝 Technologies utilisées

- **HTML5 / CSS3** - Structure et design
- **JavaScript ES6** - Logique applicative
- **Chart.js** - Visualisations graphiques
- **LocalStorage API** - Sauvegarde des données côté client

## 👨‍🏫 Auteur

**Sylvain Gorecki**  
Formateur TSMEL - Réunion  
Formation Professionnelle pour Adultes (FPA)

## 📄 Licence

Ce projet est destiné à un usage éducatif dans le cadre de la formation TSMEL.

---

## 🔗 Liens utiles

- [Référentiel TSMEL](https://www.francecompetences.fr/recherche/rncp/31629/)
- [GitHub Pages](https://sylgo974-jpg.github.io/Evaluation-initiale/)
- [Repo GitHub](https://github.com/sylgo974-jpg/Evaluation-initiale)
