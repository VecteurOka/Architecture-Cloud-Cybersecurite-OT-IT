# Système distribué de supervision mobile IIoT

## Type de projet
Projet académique – en cours  
Formation Ingénieur Architecture Logicielle & Systèmes (CNAM)

---

## Contexte
Les environnements industriels modernes nécessitent des systèmes de supervision
capables de fonctionner en temps réel, avec une forte disponibilité, une sécurité
renforcée et un accès mobile.

Ce projet s’inscrit dans une démarche Industrie 4.0 et vise à concevoir un
système distribué de supervision pour une ligne d’assemblage automobile,
basé sur une architecture multi-zones OT / Edge / IT.

---

## Objectifs
- Superviser en temps réel plusieurs installations industrielles
- Fournir une application mobile de supervision (Android)
- Garantir la haute disponibilité des flux critiques
- Sécuriser les communications industrielles (IEC 62443)
- Séparer clairement les zones OT, Edge et IT
- Intégrer calculs locaux (Edge) et consolidation IT

---

## Périmètre fonctionnel
- Supervision temps réel (KPI, télémétrie OT)
- Historisation des données industrielles
- Commandes descendantes sécurisées (MQTT)
- Visualisation mobile optimisée tablette
- Gestion des utilisateurs et des rôles
- Détection d’événements et alertes industrielles

---

## Architecture globale
Le système repose sur :
- Des installations industrielles simulées (OT)
- Une couche Edge distribuée (traitement local)
- Un cluster MQTT haute disponibilité
- Des services backend (FastAPI, WebSocket)
- Des bases de données temps réel et relationnelles
- Une application Android de supervision mobile

---

## Technologies et concepts abordés
- IIoT
- Architectures OT / Edge / IT
- MQTT (TLS, ACL, HA)
- OPC UA / Modbus TCP
- Edge Computing
- Docker & microservices
- Android (MVVM)
- Cybersécurité industrielle (IEC 62443)

---

## État du projet
🚧 Soutenance 12 juin 2026)  
Les travaux portent actuellement sur l’architecture globale,
la simulation des données industrielles et le développement
de l’application mobile Android.

---

## Positionnement
Ce projet illustre une démarche de conception orientée architecture,
avec une attention particulière portée à la résilience,
à la sécurité industrielle et à l’exploitabilité terrain.
