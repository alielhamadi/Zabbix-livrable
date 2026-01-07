# Zabbix-livrable
TP Zabbix – Supervision d’infrastructure sur AWS
🧑‍🎓 Réalisé par

Nom : Ali Elhamadi

Projet : TP Zabbix

Plateforme : AWS

Année : 2025–2026

🎯 Objectif du TP

L’objectif de ce TP est de mettre en place une solution de supervision en utilisant Zabbix, déployée sur une infrastructure AWS, afin de surveiller les performances et la disponibilité des serveurs et services.

🛠️ Technologies utilisées

Zabbix Server

Zabbix Agent

AWS EC2

Linux (Ubuntu / Amazon Linux)

MySQL / MariaDB

Apache / Nginx

Git & GitHub

🏗️ Architecture du projet

Une instance EC2 hébergeant le Zabbix Server

Une ou plusieurs instances EC2 surveillées avec Zabbix Agent

Communication entre serveur et agents via les ports Zabbix

Accès à l’interface web Zabbix via un navigateur

📌 Étapes réalisées dans ce TP
1️⃣ Création de l’infrastructure AWS

Création d’instances EC2

Configuration des Security Groups (ports Zabbix, HTTP, SSH)

Connexion aux serveurs via SSH

2️⃣ Installation de Zabbix Server

Installation du serveur Zabbix

Installation de la base de données

Configuration du frontend web Zabbix

Démarrage et vérification des services

3️⃣ Installation de Zabbix Agent

Installation de l’agent sur les machines surveillées

Configuration de l’adresse du Zabbix Server

Test de la communication agent ↔ serveur

4️⃣ Configuration dans l’interface Zabbix

Ajout des hosts

Application de templates

Surveillance des métriques (CPU, RAM, disque, réseau)

Visualisation des graphiques et alertes

5️⃣ Tests et validation

Vérification de la remontée des données

Simulation de pannes

Analyse des alertes générées par Zabbix

📊 Résultats obtenus

Supervision en temps réel des serveurs AWS

Visualisation des performances système

Détection automatique des problèmes

Centralisation de la surveillance via Zabbix

📁 Contenu du dépôt GitHub

Scripts d’installation

Fichiers de configuration

Documentation du TP

Captures d’écran (si disponibles)

🚀 Conclusion

Ce TP m’a permis de :

Comprendre le fonctionnement de Zabbix

Mettre en place une solution de supervision professionnelle

Appliquer les concepts de supervision sur une infrastructure cloud (AWS)

Renforcer mes compétences en administration système et cloud

🔗 Lien du dépôt

👉 https://github.com/alielhamadi/Zabbix-livrable
