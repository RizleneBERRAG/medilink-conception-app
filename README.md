# MediLink - TP Conception d'application

## Présentation du projet

MediLink est une application web de gestion de rendez-vous médicaux destinée à faciliter la prise de rendez-vous entre les patients et les professionnels de santé.

L'objectif principal est de proposer une solution simple, claire et efficace permettant :
- aux patients de réserver un créneau en ligne,
- aux médecins de gérer leur agenda,
- aux secrétaires d'organiser les rendez-vous,
- aux administrateurs de superviser la plateforme.

Ce projet a été conçu dans le cadre d'un TP de conception d'application afin de mettre en pratique les notions de conception logicielle, d'architecture, de modélisation, de tests, de déploiement et de maintenance.

---

## 1. Objectif de l'application

L'application MediLink répond à plusieurs problématiques réelles :

- difficulté à joindre un cabinet médical par téléphone,
- perte de temps dans la gestion manuelle des rendez-vous,
- oublis de rendez-vous,
- manque de visibilité sur les créneaux disponibles,
- besoin de centraliser les informations liées aux rendez-vous.

L'objectif est donc d'améliorer l'organisation du parcours patient et la gestion du planning médical.

---

## 2. Fonctionnalités principales

### Côté patient
- création de compte,
- connexion sécurisée,
- recherche de médecins par spécialité,
- consultation des disponibilités,
- prise de rendez-vous,
- annulation ou modification d'un rendez-vous,
- réception de rappels et notifications,
- consultation de l'historique des rendez-vous.

### Côté médecin
- gestion des disponibilités,
- consultation de l'agenda,
- visualisation des rendez-vous du jour,
- accès à la liste des patients prévus,
- ajout de notes simples après consultation.

### Côté secrétaire
- gestion manuelle des rendez-vous,
- modification du planning,
- assistance aux patients,
- traitement des annulations.

### Côté administrateur
- gestion des utilisateurs,
- gestion des rôles,
- supervision générale de l'application,
- gestion des paramètres principaux.

---

## 3. Acteurs et parties prenantes

### Acteurs principaux
- Patient
- Médecin
- Secrétaire
- Administrateur

### Parties prenantes
- équipe de développement,
- équipe de test,
- utilisateurs finaux,
- hébergeur / administrateur système,
- structure médicale ou cabinet.

---

## 4. Démarche de conception

La conception de MediLink repose sur une approche modulaire afin de garantir une forte cohésion et un faible couplage entre les différentes parties du système.

Nous avons choisi une architecture simple et évolutive, adaptée à un projet étudiant : un monolithe modulaire.

Cette approche permet :
- une meilleure lisibilité du projet,
- une maintenance plus facile,
- une meilleure testabilité,
- une évolution progressive du système.

### Principes de conception mobilisés
- SRP (Single Responsibility Principle) : chaque service possède une responsabilité unique.
- KISS : l'application reste simple et adaptée au besoin.
- YAGNI : seules les fonctionnalités utiles sont retenues.
- DRY : éviter la répétition du code et de la logique métier.

---

## 5. Architecture technique

Le projet est organisé en plusieurs modules :

- module d'authentification,
- module de gestion des utilisateurs,
- module de gestion des rendez-vous,
- module de notifications,
- module d'administration.

### Découpage technique
- Frontend : interface utilisateur
- Backend : logique métier et API
- Base de données : stockage des utilisateurs, médecins, rendez-vous et disponibilités

---

## 6. Technologies et outils

### Conception
- Figma pour les maquettes
- Draw.io / Mermaid pour les diagrammes

### Développement
- JavaScript
- React pour le frontend
- Node.js / Express pour le backend

### Base de données
- MySQL ou PostgreSQL

### Gestion de projet et versionning
- Git
- GitHub
- Trello ou Notion

### Tests
- Postman pour les tests API
- tests unitaires et fonctionnels

### Déploiement
- Vercel / Netlify pour le frontend
- Render / Railway / VPS pour le backend

---

## 7. Processus de création

### Conception
- analyse du besoin,
- identification des acteurs,
- définition des fonctionnalités,
- création des maquettes,
- modélisation UML,
- choix de l'architecture.

### Développement
- création de l'interface utilisateur,
- implémentation de l'API,
- création des modèles de données,
- mise en place des routes,
- séparation en controllers / services / models.

### Test
- tests unitaires,
- tests d'intégration,
- tests fonctionnels,
- tests de validation utilisateur.

### Déploiement
- préparation de l'environnement,
- configuration de la base de données,
- mise en ligne du frontend et du backend,
- activation du HTTPS.

### Maintenance
- correction des bugs,
- amélioration des performances,
- ajout progressif de nouvelles fonctionnalités,
- mises à jour de sécurité.

---

## 8. Schémas et diagrammes

Les diagrammes du projet sont disponibles dans le dossier `docs/diagrammes`.

Ils présentent :
- les acteurs du système,
- la structure générale de l'application,
- le scénario de réservation d'un rendez-vous.

---

## 9. Pourquoi ce projet est pertinent

MediLink est un projet pertinent car il répond à un besoin réel et permet d'aborder les principales notions vues en cours :
- conception logicielle,
- séparation des responsabilités,
- cohésion et couplage,
- architecture modulaire,
- modélisation du domaine,
- tests,
- déploiement,
- maintenance.

---

## 10. Conclusion

MediLink est une application de prise de rendez-vous médicaux pensée pour être simple, utile et évolutive.

Ce projet montre une démarche complète allant de l'analyse du besoin jusqu'à la maintenance, en passant par la conception, le développement, le test et le déploiement.

Il illustre également l'importance d'une bonne conception logicielle avant l'implémentation.