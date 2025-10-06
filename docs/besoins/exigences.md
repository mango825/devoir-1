---
title: Analyse des besoins - Exigences
---

# Exigences

## Exigences fonctionnelles

TODO: Liste des fonctions que le système doit accomplir.


- [ ] EF1 : L'utilisateur peut créer un nouveau compte étudiant.
- [ ] EF2 : L'utilisateur peut effectuer une nouvelle connexion à un compte étudiant.
- [ ] EF3 : L'utilisateur peut modifier ses préférences dans son profil.
- [ ] EF4 : L'étudiant peut effectuer des recherches des cours spécifiques.
- [ ] EF5 : L'étudiant peut obtenir des résultats recommandés et personnalisés.
- [ ] EF6 : L'étudiant peut voir les détails des cours sélectionnés, comme la charge de travail et les moyennes.
- [ ] EF7 : L'étudiant peut voir les avis des anciens étudiants sur les cours sélectionnés.

## Exigences non fonctionnelles

TODO: Contraintes de performance, sécurité, compatibilité, etc.


- [ ] ENF1 : Le système doit répondre en moins de 2 secondes.
- [ ] ENF2 : L'application doit être compatible avec Chrome et Firefox.
- [ ] ENF3 : Le système est facilement accessible, clair et utile. 
- [ ] ENF4 : Le système ne divulgue pas d'informations confidentielles. 
- [ ] ENF5 : Les données officielles sont centralisées dans une même interface. 

## Priorisation

TODO: Identifier les exigences critiques.

## Types d'utilisateurs

> Identifier les différents profils qui interagiront avec le système.

| Type d’utilisateur | Description | Exemples de fonctionnalités accessibles |
|--------------------|-------------|------------------------------------------|
| Utilisateur invité | Accès limité, pas d’authentification | Consultation des ressources |
| Utilisateur authentifié | Compte personnel, fonctions principales | Réservation, historique |
| Administrateur | Droits étendus, gestion des ressources | Création/suppression de ressources, gestion des utilisateurs |

<!-- TODO: Détailler selon le périmètre du projet. -->

## Infrastructures

> Informations sur l’environnement d’exécution cible, les outils ou plateformes nécessaires.

- Le système sera hébergé sur un serveur Ubuntu 22.04.
- Base de données : PostgreSQL version 15.
- Serveur Web : Nginx + Gunicorn (pour une app Python, par exemple).
- Framework principal : [À spécifier selon le projet].

<!-- TODO: Compléter selon le stack technique prévu. -->