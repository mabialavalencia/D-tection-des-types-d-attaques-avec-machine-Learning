# D-tection-des-types-d-attaques-avec-machine-Learning
Développement d'un pipeline de machine learning end-to-end pour identifier et classer les types d'attaques cybernétiques à partir de données réseau

## Projet : Détection des types d'attaques

### Contexte du Projet
Ce projet repose sur l'analyse d'un jeu de données intitulé `cybersecurity_attacks.csv`, qui regroupe environ 40,000 enregistrements et 25 métriques relatives à des événements de cybersécurité. Le fichier contient des logs bruts issus d’un système de surveillance réseau, permettant d’identifier différents types d’attaques telles que les attaques DDoS, les intrusions, et les infections par malware.

### Caractéristiques du Jeu de Données
- **Timestamp** : La date et l’heure de l’événement.
- **IP Addresses** : Source et destination des adresses IP impliquées.
- **Ports** : Source et destination des ports utilisés pour l'échange de données.
- **Protocol** : Le protocole de communication utilisé (TCP, UDP, ICMP, etc.).
- **Packet Information** : Longueur et type des paquets, nature du trafic.
- **Security Indicators** : Payload Data, Malware Indicators, Anomaly Scores, Alerts/Warnings.
- **Classification** : Attack Type, Attack Signature, Action Taken, Severity Level.
- **Additional Context** : User Information, Device Information, Network Segment, Geo-location, Proxy Information, Firewall Logs, IDS/IPS Alerts, Log Source.

### Objectifs du Projet
L’objectif principal de ce projet est de développer un pipeline de machine learning end-to-end pour :
- Nettoyer et prétraiter les données brutes.
- Réaliser une ingénierie des caractéristiques avancée.
- Entraîner et comparer plusieurs modèles de machine learning (RandomForest, LightGBM, CatBoost).
- Déployer le modèle final dans une application web (utilisant Flask) pour des prédictions en temps réel.

### Contexte d’Utilisation
Cette solution pourrait être utilisée par des organisations de cybersécurité pour :
- Surveiller en continu le trafic réseau et détecter des activités malveillantes.
- Analyser les logs d'attaque pour une réponse efficace aux menaces.
- Optimiser la réponse aux incidents par une automatisation de l'identification des attaques et la mise en place de mesures de sécurité adaptées.

