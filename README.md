# 🛠️ GLPI Network Management and Security Guide

![Banner](Img/back.png)

[![GLPI](https://img.shields.io/badge/GLPI-009688?style=flat-square&logo=glpi&logoColor=white)](https://glpi-project.org/) [![LDAP](https://img.shields.io/badge/LDAP-000080?style=flat-square&logo=ldap&logoColor=white)](https://ldap.com/) [![MySQL](https://img.shields.io/badge/MySQL-00758F?style=flat-square&logo=mysql&logoColor=white)](https://www.mysql.com/) [![Apache](https://img.shields.io/badge/Apache-D22128?style=flat-square&logo=apache&logoColor=white)](https://httpd.apache.org/) [![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)](https://www.php.net/)

## 📊 Table des Matières

1. [Introduction](#1-introduction)  
2. [Contexte](#2-contexte)  
3. [Fonctionnalités de GLPI](#3-fonctionnalités-de-glpi)  
4. [Structure du Repository](#4-structure-du-repository)  
5. [Partie Pratique](#5-partie-pratique)  
6. [Gestion des Utilisateurs](#6-gestion-des-utilisateurs-partie-2)  
7. [Configuration de l'annuaire LDAP](#7-configuration-de-lannuaire-ldap-dans-glpi)  
8. [Gestion des Tickets d’Incident](#8-gestion-des-tickets-dincident)  
9. [Gestion des Connexions Réseaux](#9-gestion-des-connexions-réseaux)  
10. [Gestion des Imprimantes](#10-gestion-des-imprimantes)  

---

## 📚 4. Structure du Repository

### 📂 **Repository Content**

- **`Directives_Rapport_GLPI/`**  
  Contient les directives et rapports de travaux pratiques.

- **`Doc/`**  
  Documentation complète des configurations, explications des choix techniques et gabarits GLPI.

- **`Img/`**  
  Images et captures d’écran pour illustrer les étapes de configuration et d’analyse des logs.

- **`README.md`**  
  Guide détaillé du projet avec instructions pour la configuration et la gestion du parc informatique.

- **`back.png`**  
  Image de bannère utilisée pour le README.

---

## 🎨 5. Partie Pratique

### 🛠️ Création des Statuts des Matériels

1. Allez dans **Configuration > Statuts**.
2. Créez des statuts personnalisés pour chaque type de matériel (ex : PC, Serveur, Imprimante).

### 🛡️ Ajout de Systèmes d’Exploitation

1. Accédez à **Inventaire > Systèmes d’Exploitation**.
2. Ajoutez les OS utilisés (Windows, Linux, macOS).

### 🏰 Création des Lieux et des Salles

1. Allez dans **Administration > Lieux**.
2. Ajoutez les différents bâtiments, étages et salles.

---

## 👥 6. Gestion des Utilisateurs (Partie 2)

- Synchronisez les utilisateurs avec **LDAP**.
- Définissez les rôles et permissions pour chaque utilisateur selon les besoins de votre organisation.

---

## 🔧 7. Configuration de l'Annuaire LDAP

1. Accédez à **Configuration > Authentification > LDAP**.
2. Renseignez les informations de connexion LDAP.
3. Testez la synchronisation pour vérifier que les utilisateurs sont importés correctement.

---

## 🛡️ 8. Gestion des Tickets d’Incident

1. Allez dans **Assistance > Tickets**.
2. Créez des tickets d'incident, affectez-les aux techniciens et suivez le statut.

---

## 🛢️ 9. Gestion des Connexions Réseaux

- Créez des équipements réseau comme des commutateurs et routeurs.
- Documentez les connexions physiques avec des plans de réseau.

---

## 💻 10. Gestion des Imprimantes

- Ajoutez les imprimantes via **Inventaire > Périphériques**.
- Gérez les consommables et définissez les alertes pour le remplacement des cartouches.

---

## 📦 Resources

- **Site Officiel de GLPI** : [GLPI Project](https://glpi-project.org)  
- **Documentation Officielle** : [GLPI Docs](https://glpi-docs.readthedocs.io)

---

### 📅 Auteur

**Eloham Caron**  
13 Décembre 2024
