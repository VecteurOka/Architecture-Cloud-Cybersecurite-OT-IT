# POC Digital Twin industriel synchronisé Edge / Cloud

## Type de contenu
Expérimentation / POC académique  
Formation Ingénieur Architecture Logicielle & Systèmes

---

## Contexte
Les architectures industrielles modernes intègrent de plus en plus le concept
de **Digital Twin** afin de représenter, analyser et anticiper le comportement
des équipements physiques.

Dans un contexte IIoT, la mise en œuvre d’un jumeau numérique pose des
contraintes spécifiques liées à la **latence**, à la **cohérence des données**
et à la **résilience des communications** entre les couches OT, Edge et Cloud.

Ce POC vise à explorer ces problématiques à travers une expérimentation
contrôlée et volontairement simplifiée.

---

## Objectif
Expérimenter la synchronisation d’un jumeau numérique industriel entre une
couche **Edge** et une plateforme **Cloud**, en analysant :

- la latence de synchronisation Edge / Cloud,
- la cohérence des états du jumeau numérique,
- le comportement du système en cas de perte de connectivité,
- les limites techniques du modèle retenu.

---

## Périmètre de l’expérimentation
- Jumeau numérique simplifié d’un équipement industriel
- Données simulées (capteurs, états machine)
- Traitement partiel au niveau Edge
- Synchronisation périodique avec le Cloud
- Aucun pilotage réel d’équipement industriel

---

## Axes d’expérimentation
- Synchronisation des états Edge ↔ Cloud
- Gestion des délais et des décalages temporels
- Dégradation du service en cas de coupure réseau
- Reprise et resynchronisation après incident
- Impact des fréquences de mise à jour

---

## Livrables
Ce POC aboutit aux livrables suivants :

- Architecture du POC Digital Twin (Edge / Cloud)
- Analyse des limites techniques observées
- Retours d’expérimentation et enseignements
- Pistes d’amélioration pour une architecture industrielle réelle

---

## Contenu du dépôt

### 📁 architecture/
Schémas d’architecture :
- Positionnement Edge / Cloud
- Flux de données
- Synchronisation du jumeau numérique

### 📁 experiments/
Résultats et observations :
- Latence de synchronisation
- Cohérence des données
- Scénarios de panne et de reprise

### 📁 implementation-notes/
Notes techniques :
- Choix de conception
- Hypothèses et simplifications
- Paramètres d’expérimentation

### 📁 conclusions/
Synthèse du POC :
- Ce qui fonctionne
- Ce qui ne fonctionne pas
- Limites identifiées
- Enseignements pour des projets futurs

---

## Concepts abordés
- Digital Twin
- IIoT
- Edge Computing
- Architectures OT / Cloud
- Synchronisation des données
- Résilience et tolérance aux pannes

---

## Positionnement
Ce travail est un **POC académique**, dont l’objectif est d’explorer et de
comprendre les contraintes techniques liées aux architectures Digital Twin
industrielles.

Il ne s’agit pas d’un produit final, mais d’une expérimentation destinée à
éclairer des choix d’architecture dans un contexte OT / Edge / Cloud.
``
