# Brocéliande Immo - Plateforme Immobilière

## Description
Brocéliande Immo est une application web PHP permettant la gestion d'annonces immobilières et la mise en relation entre agents immobiliers et clients. Le site propose des fonctionnalités de consultation d'annonces, d'inscription/connexion utilisateur et de prise de contact.

## Fonctionnalités

### Côté Client
- Consultation des annonces (vente et location)
- Inscription et connexion utilisateur
- Formulaire de contact avec les agents
- Visualisation des agences (Rennes, Quimper, Vannes)
- Prise de rendez-vous

### Gestion des Biens
- Affichage des biens en vedette
- Détails des propriétés avec galerie photos
- Filtrage par type de transaction (vente/location)
- Mise en ligne de nouveaux biens

## Technologies Utilisées
- PHP
- MySQL
- HTML5
- CSS3
- Bootstrap 4.5.2
- jQuery
- Font Awesome 5.15.4

## Structure de la Base de Données
```sql
Database: brocelianimmo

Table: users
- mail (varchar)
- pass (varchar)
```

## Installation
1. Installer XAMPP
2. Cloner le projet dans le dossier `htdocs`
3. Importer la base de données `brocelianimmo.sql`
4. Configurer les accès base de données dans les fichiers:
   - `traitement_connexion.php`
   - `traitement_inscription.php`
5. Démarrer Apache et MySQL
6. Accéder au site via: `http://localhost/ProjetAgenceImmoV1/`

## Architecture des Fichiers
```
ProjetAgenceImmoV1/
├── Images/
├── agencequimper.php
├── agencerennes.php
├── agencevannes.php
├── annonce1.php
├── annonce2.php
├── annonce3.php
├── annonce4.php
├── annonces.php
├── connexion.php
├── index.php
├── inscription.php
├── location.php
├── Rdv.php
├── styles.css
├── traitement_connexion.php
├── traitement_contact.php
├── traitement_inscription.php
├── user_connected.php
├── vendre.php
└── vente.php
```

## Auteur
[Votre nom]

## License
© 2024 Brocéliande Immo. Tous droits réservés.