# Travail de Recherche et d'Expérimentation : Sécurité des Mots de Passe

## Introduction
Ce projet a pour but d'explorer les bonnes pratiques de gestion des mots de passe, d'expérimenter les attaques par force brute et dictionnaire, et d'examiner l'utilisation de gestionnaires de mots de passe. Il met également l'accent sur la mise en œuvre concrète de la sécurité des mots de passe à l'aide d'outils disponibles sur une distribution Debian.

## Bonnes Pratiques
### Complexité des Mots de Passe
Les mots de passe doivent être :
- **Longs** : Un mot de passe de 12 caractères minimum est recommandé.
- **Complexes** : Utiliser des majuscules, minuscules, chiffres et symboles spéciaux.
- **Uniquement uniques** : Chaque mot de passe doit être distinct et ne pas être réutilisé.

### Renouvellement des Mots de Passe
Les mots de passe doivent être renouvelés régulièrement (par exemple tous les 3 à 6 mois) pour réduire le risque d'accès non autorisé en cas de fuite de données.

### Moyens Mnémotechniques
Des techniques comme l'utilisation de phrases longues et uniques ou l'utilisation de gestionnaires de mots de passe peuvent aider à mémoriser des mots de passe complexes tout en garantissant leur sécurité.

## Attaque par Force Brute et Dictionnaire
### Objectif
Apprendre à utiliser des outils sur Debian pour réaliser une attaque par force brute ou dictionnaire sur un mot de passe.

### Outils Utilisés
- **John the Ripper** : Outil pour les attaques par force brute.
- **Hydra** : Outil pour les attaques par dictionnaire.

### Étapes
1. Utilisation de **John the Ripper** ou **Hydra** pour attaquer un mot de passe en utilisant un dictionnaire contenant des mots basés sur des informations personnelles.
2. Configuration des attaques sur un service spécifique (exemple : SSH, FTP) sur la machine cible.

## Gestion des Mots de Passe
### Fonctionnalités des Gestionnaires de Mots de Passe
Les gestionnaires de mots de passe offrent plusieurs fonctionnalités importantes pour la gestion sécurisée des identifiants :
- **Stockage crypté** des mots de passe.
- **Génération de mots de passe forts**.
- **Sauvegarde et synchronisation** entre plusieurs appareils.
- **Partage sécurisé** de mots de passe.

### Logiciels Disponibles sur Debian
Voici quelques gestionnaires de mots de passe populaires disponibles sur Debian :
- **KeePassX** : Un gestionnaire de mots de passe léger et open-source.
- **Bitwarden** : Un gestionnaire de mots de passe en ligne avec un client open-source.
- **Password Safe** : Une autre option populaire pour la gestion des mots de passe.

### Mise en œuvre d'un Gestionnaire de Mots de Passe
1. Installation et configuration d'un gestionnaire de mots de passe sur une machine Debian.
2. Utilisation du gestionnaire pour stocker et organiser des mots de passe.
3. Utilisation de la fonctionnalité de génération de mots de passe pour créer des mots de passe forts.

## Conclusion
Ce travail montre l'importance des bonnes pratiques en matière de gestion des mots de passe, tout en explorant les risques liés à une mauvaise gestion et les outils disponibles pour attaquer un système mal protégé. Les gestionnaires de mots de passe sont essentiels pour assurer la sécurité des informations personnelles et professionnelles.

## Compétences Acquises
- **Gestion des mots de passe** : Création de mots de passe sécurisés et gestion avec des outils dédiés.
- **Sécurité informatique** : Compréhension des attaques par force brute et dictionnaire.
- **Ethical hacking** : Utilisation d'outils comme **Hydra**, **John the Ripper** et **Nmap**.
- **Sécurisation des informations** : Mise en place de solutions sécurisées pour protéger ses mots de passe.

## Prérequis
- Un environnement Debian ou similaire pour installer et utiliser les outils.
- Connaissances de base en ligne de commande et gestion des machines virtuelles (VirtualBox, Kali Linux).

## Références
- [MOOC de l'ANSSI sur la sécurité informatique](https://www.ssi.gouv.fr/formation/)
- Documentation sur les outils utilisés : 
  - [John the Ripper](https://www.openwall.com/john/)
  - [Hydra](https://github.com/vanhauser-thc/thc-hydra)
  - [KeePassX](https://www.keepassx.org/)
  - [Bitwarden](https://bitwarden.com/)
