# Stratégie de Sécurité de l'Application CaloriesTracker

## Introduction

Pour la sécurité de notre application, nous avons mis en place differentes mesures de protection reparties en trois axes prioritaires. CaloriesTracker vise à soutenir tous ceux qui aspirent à atteindre leurs objectifs physiques.

## Les Principaux Axes

Nous nous concentrerons sur trois grands axes :
- Protéger les données personnelles.
- Assurer une identification sécurisée.
- Garantir la sécurité du client.

## La Mise en Place

### La Protection des Données Personnelles

- Appliquer le principe du Moindre Privilège pour limiter les risques de vol ou de destruction de données.
- Utiliser le protocole HTTPS pour sécuriser les échanges de données.
- Mettre en place une Politique de Sécurité du Contenu (CSP) pour sécuriser les interactions avec l’API.

### La Sécurité Liée aux Mots de Passe

- Limiter l’accès après un nombre défini de tentatives échouées (8) pour contrer les attaques en ligne.
- Utiliser le hachage et le salage des mots de passe pour renforcer leur sécurité.
- Exiger des mots de passe avec une complexité minimale et une longueur adéquate.
- Envoyer des notifications en cas d'activité suspecte.

### La Sécurité Liée à l’Expérience Utilisateur

- Adopter une approche de défense en profondeur pour prévenir les attaques.
- Limiter la surface d’attaque en appliquant des politiques strictes telles que HSTS et SOP.
- Utiliser des mécanismes de protection contre les vulnérabilités XSS et CORS.
- Séparer clairement les composants web (HTML, CSS, JavaScript) pour renforcer la sécurité.

## Éléments Supplémentaires pour une Stratégie de Sécurisation

- Mettre en place une politique d'identification et de gestion des accès (IAM).
- Effectuer régulièrement des tests de sécurité et des audits.
- Instaurer un système de surveillance pour détecter les activités suspectes.
- Sensibiliser le personnel aux bonnes pratiques de sécurité.
- Rester informé des dernières menaces et des meilleures pratiques de sécurité.
