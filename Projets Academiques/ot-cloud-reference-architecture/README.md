# Architecture de référence OT → Cloud pour environnement industriel

## Type de projet
Projet académique  
Formation Ingénieur Génie Logiciel

---

## Contexte
Les environnements industriels connectés nécessitent des architectures capables
de remonter des données OT vers des plateformes IT et Cloud de manière fiable,
sécurisée et résiliente.

Ce projet vise à définir une **architecture de référence OT → Cloud** adaptée
aux contraintes industrielles, intégrant la gestion des flux intermittents,
la tolérance aux pannes et les principes de résilience.

---

## Objectif
Définir une architecture de référence OT → Cloud permettant la remontée fiable
et sécurisée des données industrielles, en intégrant :

- la séparation des zones OT / Edge / IT,
- des mécanismes de résilience et de tolérance aux pannes,
- la gestion des interruptions de connectivité,
- des flux adaptés aux contraintes industrielles.

---

## Livrables
- Architecture cible OT / Cloud
- Diagrammes de flux industriels
- Justification des choix d’architecture
- Analyse des mécanismes de résilience

---

## Contenu du dépôt

### 📁 architecture/
Schémas d’architecture de référence :
- vues globales OT / Cloud
- zones fonctionnelles
- positionnement des composants

### 📁 flows/
Description des flux OT → Cloud :
- télémétrie
- commandes
- historisation
- supervision

### 📁 resilience/
Mécanismes de résilience :
- tolérance aux pannes
- gestion des flux intermittents
- patterns Store & Forward

### 📁 decisions/
Justification des choix d’architecture :
- Edge vs Cloud
- protocoles
- modèles de communication

### 📁 conclusions/
Synthèse et enseignements :
- limites de l’architecture
- conditions de mise en œuvre réelle
- pistes d’amélioration

---

## Positionnement
Ce projet constitue une **architecture de référence** et non un produit fini.
Il vise à servir de base de réflexion pour la conception de systèmes industriels
connectés OT / Cloud dans un contexte académique.
