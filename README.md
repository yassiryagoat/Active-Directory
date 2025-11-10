# Active Directory - TP

##  Introduction
Ce dépôt contient les travaux pratiques réalisés dans le cadre d’un TP sur l’installation et la gestion d’Active Directory sur Windows Server 2012. L’objectif principal est de mettre en place un contrôleur de domaine, configurer des clients, appliquer des stratégies de groupe (GPO) et assurer la sécurité dans un environnement Windows.

##  Objectifs
- Créer et configurer un serveur Active Directory Domain Services (ADDS)
- Créer un domaine et ajouter des clients au domaine
- Gérer les unités organisationnelles (OU) et les comptes utilisateurs
- Créer et appliquer des stratégies de groupe (GPO)
- Sécuriser l’environnement via des politiques de sécurité avancées
- Tester et exploiter les services AD et SMB

##  Déroulement Technique
Les fichiers PDF détaillent étape par étape :
- Mise en place de l’infrastructure avec plusieurs machines virtuelles (DC, clients Windows 7/10, poste externe)
- Installation et configuration d’Active Directory
- Création des OUs et comptes utilisateurs via PowerShell
- Application et vérification des stratégies GPO (mot de passe, verrouillage de session, restrictions d’accès…)
- Enumération et analyse de la sécurité SMB (dont exploitation de vulnérabilités comme MS17-010 et Zerologon)

##  Contenu du dépôt
- `Compte rendu - Installation de l'AD.pdf` : Description des étapes principales d’installation d’Active Directory
- `Rapport de TP1 AD.pdf` : Rapport de l’installation et configuration d’AD et GPO
- `Rapport TP2.pdf` : Sujets avancés et tests de sécurité sur SMB, enumération et exploitation

##  Pour aller plus loin
- Test des GPO sur différents postes et comptes
- Analyse des vulnérabilités et exploitation via Nmap, Metasploit
- Restriction logicielle et sécurisation avancée des postes étudiants

##  Contributeur
- Yassir Yagoat (Auteur, référent du TP)

---

> **Remarque :** Ce dépôt est un support pédagogique destiné à la formation et l’expérimentation en environnement sécurisé.

