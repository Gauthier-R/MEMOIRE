# Introduction
## Contexte : L'explosion des données massives (Big Data) et leur rôle central dans les processus décisionnels des entreprises.

## Problématique : Comment assurer la fiabilité et la durabilité des solutions de Business Intelligence (BI) à travers une gouvernance efficace des données massives ?

## Objectifs : Identifier les procédures et initiatives clés en matière de gouvernance des données pour soutenir des solutions BI robustes.

## Méthodologie : Analyse documentaire, études de cas, entretiens avec des experts du domaine.

# Partie 1 : Fondements de la gouvernance des données massives
## 1.1. Définition et enjeux du Big Data

### 1.1.1 Qu'est ce qu'une donnée ?

Explication des données, ou en trouve t on, ce que ça représente (volume, vie de tous les jours), quels sont les types de données que l'on trouve (données personnelles, données sensibles etc)

Introduction à mon cas d'entreprise -> mon rôle en tant qu'apprenti data analyst -> nous sommes amenés à manipuler de nombreuses données personnelles et sensible ( cas de la santé )

Source : 
- Liens_Données / 1. CNIL – Définition de la donnée personnelle / https://www.cnil.fr/fr/definition/donnee-personnelle
- Liens_Données / 8. CNIL - Définition d'une donnée sensible / https://www.cnil.fr/fr/definition/donnee-sensible

### 1.1.2 L'origine du Big Data

Depuis quand est qu'on parle de cela, quel en est la cause, comment évolue cette notion, qu'est ce qu'elle représente principalement aujourd'hui, qu'est-ce que les données structurées et non structurées,

Cas d'exemple avec les données clients et gestion des contrats -> trouver des chiffres sur alptis par rapport au nombre de clients, nombre de contrats gérés, les courtiers etc -> Aller chercher dans mes powerpoints

Source :
- Liens_Données / 2. Crédit Mutuel – À quoi servent nos données sur Internet ? / https://www.creditmutuel.fr/fr/particuliers/informations/confidentialite-donnees-internet.html -> Afin d'avoir des infos génériques sur la consommation de la donnée aujourd'hui
- Liens_Données / 4. Oracle – Qu’est-ce que le Big Data ? / https://www.oracle.com/fr/big-data/what-is-big-data/
- Liens_Données / 3. SAP – Qu'est-ce que le Big Data ? / https://www.sap.com/france/products/technology-platform/what-is-big-data.html
- Liens_Données / 5. Adobe – Qu’est-ce que le Big Data ? / https://business.adobe.com/fr/blog/basics/big-data
- Liens_Données / 6. CNIL – Définition du Big Data / https://www.cnil.fr/fr/definition/big-data

### 1.1.3 Caractéristiques des données massives : volume, variété, vélocité, véracité, valeur.

Qu'est ce qui nous permet de définir une big Data, expliquer chacune des caractéristiques

Source :
- Liens_Données / 4. Oracle – Qu’est-ce que le Big Data ? / https://www.oracle.com/fr/big-data/what-is-big-data/
- Liens_Données / 3. SAP – Qu'est-ce que le Big Data ? / https://www.sap.com/france/products/technology-platform/what-is-big-data.html
- Liens_Données / 5. Adobe – Qu’est-ce que le Big Data ? / https://business.adobe.com/fr/blog/basics/big-data

### 1.1.4 Défis associés au Big Data : gestion, stockage, traitement, sécurité.

Comment manipuler ces données, quels enjeux, le coût et ce que ça rapporte

Projet segmentation portefeuille avec problème d'extraction des données via excel (outil non adapté pour des volumes énormes de données)

Source :
- Liens_Données / 7. Talend – L’avenir du Big Data / https://www.talend.com/fr/resources/future-big-data/
- Liens_Données / 4. Oracle – Qu’est-ce que le Big Data ? / https://www.oracle.com/fr/big-data/what-is-big-data/
- Liens_Données / 3. SAP – Qu'est-ce que le Big Data ? / https://www.sap.com/france/products/technology-platform/what-is-big-data.html
- Liens_Données / 5. Adobe – Qu’est-ce que le Big Data ? / https://business.adobe.com/fr/blog/basics/big-data

## 1.2. Concepts clés de la gouvernance des données

### 1.2.1 Qu'est ce que la gouvernance ?

L'ensemble des processus, politiques et normes pour gérer les données efficacement et les avantages que cela procure 

S'appuyer sur les définitions données dans le ppt alptis / Parler de cette volontée de développer la gouvernance

Source :
- PPT Gouvernance des données Alptis
- Gouvernance / 1. Google Cloud – Qu'est-ce que la gouvernance des données ? / https://cloud.google.com/learn/what-is-data-governance?hl=fr
- Gouvernance / 2. Talend – Gouvernance des données : principe, utilité et outils / https://www.talend.com/fr/resources/guide-gouvernance-donnees/
- Gouvernance / 3. SAP – Qu'est-ce que la gouvernance des données ? / https://www.sap.com/suisse/products/data-cloud/master-data-governance/what-is-data-governance.html
- Gouvernance / 4. Oracle – Qu’est-ce que la gouvernance des données ? / https://www.oracle.com/fr/security/definition-data-governance/

### 1.2.2 Les objectifs d'une gouvernance fonctionnelle

Objectifs : qualité, sécurité, conformité, accessibilité des données. Développer ces notions et points de vues

Les actions mises en place par Altpis pour y répondre et illustrer ces propos : Commentaires des tables, tdb suivis des erreur dans nos données, sensibilisation du métier

Source :
- PPT Gouvernance des données Alptis


--------------- JE NE SAIS PAS QUOI FAIRE DE CETTE PARTIE -----------------
## 1.3. Cadres et référentiels de gouvernance

### 1.3.1 Présentation des principaux frameworks : DAMA-DMBOK, COBIT, DCAM.

Parler des outils et méthodes recommandées / les plus courantes afin de répondre à une gouvernance efficace 

Processus de réflexion et travail sur ce projet

### 1.3.2 Comparaison des approches : top-down, bottom-up, Data Mesh. 

Comment adapter sa gouvernance en fonction du besoin

Exemple d'approche choisi par Alptis, méthode Agile de travail ? 
------------------------------------------------------------------------


# Partie 2 : Intégration de la gouvernance des données dans les solutions BI
## 2.1. Importance de la gouvernance pour la BI

### 2.1.1 Qu'est ce que la BI.

Définir la BI, son rôle, depuis quand est ce qu'on en parle, ce que ça apporte

Parler des nombreux projets BI fait chez Alptis : conception des tableaux de bords QS et rapports BO

### 2.1.2 Assurer la qualité et la fiabilité des analyses.

Faire le lien entre BI et gouvernance, parler de l'importance de restituer des valeurs justes sinon plus aucun sens (chose complexe) et parler de l'importance de comprendre le besoin

Les nombreux échanges fait avec le métier afin de définir leur besoin et de le retranscrire de manière correcte en données

### 2.1.3 Favoriser une prise de décision éclairée en limitant les incohérences. 

C'est une démarche longue et qui nécessite de la régularité à mettre en place, mais qui par la suite donnera de bonne habitude, un gain de temps et de justesse donc d'argent (amélioration de la qualité de la stratégie et prise de décision)

## 2.2. Composants clés d'une gouvernance efficace pour la BI

### 2.2.1 Gestion de la qualité des données : exactitude, complétude, cohérence.

Parler de l'importance d'avoir des données juste et comment faire (anticipation, réflexion en amont, structure du modèle de données, pratiques de dev)

Le projet de refonte de l'outil de gestion Cleva -> réflexion sur le datawarehouse, enrichissement, controle qualité au travers de rapports bo

### 2.2.2 Sécurité et confidentialité des données.

Importance de sécuriser ses données, gérer les droits d'accès etc

Données autour de la santé sont hyper règlementées, les rapports nécessitent des droits d'accès en fonction du type de données.

### 2.2.3 Traçabilité et compréhension des données.

Importance de versionner et commenter ses dev, les tables, les champs 

Citation de l'utilisation d'outils tel que Git hub, draw.io etc

### 2.2.4 Catalogage et métadonnées. 

Importance d'avoir à la fois une compréhension technique mais aussi fonctionnelle des données : par exemple être capable de retranscrire une données en fonction métier. Utilisation de métadonnées pour définir des données (voir comment développer la notion) 

Mettre en avant les outils spécialisés dans le cataloguage de données  : Data Galaxy

## 2.3. Rôles et responsabilités

### 2.3.1 Chief Data Officer (CDO), Data Steward, Data Owner.

Présenter les profils typiques des personnes garantes de la gouvernance des données.

Mettre en avant les échanges fait entre data steward, owner etc chez alptis afin de garantir des livraisons en prd péraines

### 2.3.2 Collaboration entre les équipes IT et métiers.

Parler des échanges mis en places avec le métier et l'intérêt de data galaxy

### 2.3.? Sensibilisation des utilisateurs de la donnée

l'envie de sensibiliser le métier en leur donnant la main sur des sandbox, d'être amené à manipuler la données en leur montrant les étapes de transition afin de repondre fidèlement  à leur besoin

# Partie 3 : Initiatives et meilleures pratiques pour une gouvernance durable
## 3.1. Mise en place de politiques et procédures

### 3.1.1 Élaboration de politiques de gouvernance alignées sur les objectifs stratégiques.

### 3.1.2 Définition de standards et de processus pour la gestion des données. 

## 3.2. Adoption d'outils et technologies

### 3.2.1 Utilisation de solutions de gestion de la qualité des données, de catalogues de données, de plateformes de gouvernance.

### 3.2.2 Intégration avec les outils BI existants. 

## 3.3. Formation et culture organisationnelle ? (ou alors directement fusionné avec la 3.1 ? )

### 3.3.1 Sensibilisation des collaborateurs à l'importance de la gouvernance des données.

### 3.3.2 Développement d'une culture axée sur la qualité et la responsabilité des données. 

## 3.4. Conformité réglementaire

### 3.4.1 Respect des réglementations en vigueur : RGPD, Data Governance Act.

### 3.4.2 Mise en place de mécanismes de contrôle et d'audit. 

# Conclusion
Synthèse : Récapitulation des procédures et initiatives essentielles pour une gouvernance efficace des données massives au service de la BI.

Limites : Contraintes identifiées lors de l'étude.

Perspectives : Évolutions futures de la gouvernance des données avec l'émergence de nouvelles technologies et réglementations.

# Bibliographie
Sélection d'ouvrages, articles académiques, rapports d'experts et sources en ligne pertinents.
