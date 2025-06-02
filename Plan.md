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



## 1.3. Cadres et référentiels autour de la gouvernance

### 1.3.1 Vue d'ensemble des principaux cadres de référence

Parler des outils, méthodes et recherches faites autour de la gouvernance. Montrer que cette notion de gouvernance n'est pas récente et qu'elle évolue constamment. 
( C'est comme ranger ta chambre )  

S'appuyer sur des références reconnues dans la recherche de la gouvernance comme ces livres : DAMA-DMBOK, COBIT, DCAM -> pas certain de celle la

Source : 
- Framework / 1. DAMA-DMBOK (Data Management Body of Knowledge)
- Framework / 2. COBIT (Control Objectives for Information and Related Technologies)
- Framework / 3. DCAM (Data Management Capability Assessment Model)

### 1.3.2 Comparaison des approches : top-down, bottom-up, Data Mesh. 

Comment adapter sa gouvernance en fonction du besoin. Montrer que la mise en œuvre opérationnelle dépend aussi de la culture de l’entreprise, de sa structure, de sa maturité et de ses objectifs.

Exemple : Mettre en valeur les process mis en place par Alptis, méthode Agile de travail, catalogue de données, échange avec le métier, architecture des données ...

Source : 
- Framework / 4. Top down et bottom up
- Framework / 5. Data Mesh



# Partie 2 : Intégration de la gouvernance des données dans les solutions BI
## 2.1. Importance de la gouvernance pour la BI

### 2.1.1 Qu'est ce que la BI.

Définir la BI, son rôle, depuis quand est ce qu'on en parle, ce que ça apporte

Parler des nombreux projets BI fait chez Alptis : conception des tableaux de bords QS et rapports BO

Source :
- BI / 1. Oracle – Définition de la Business Intelligence / https://www.oracle.com/fr/database/business-intelligence-definition/
- BI / 2. Tableau – Définition et importance de la BI / [https://www.oracle.com/fr/database/business-intelligence-definition/](https://www.tableau.com/en-gb/trial/business-intelligence-software?d=701ed00000DQp8eAAD&nc=701ed00000DRihWAAT&utm_content=701ed00000DQp8eAAD&utm_source=google&utm_medium=paid_search&utm_campaign=22284130994&utm_adgroup=173946811565&utm_term=business%20intelligence&utm_matchtype=e&gad_source=1&gad_campaignid=22284130994&gbraid=0AAAAAqUgRK8dC_b9ZNOx2hGm-_hlH6Nxh&gclid=CjwKCAjw3MXBBhAzEiwA0vLXQaIiW_Uh1z2pJmcG1z7rZXRQdbdG7i0VzJj2v0yDz110vUF_KQOcYxoCvDwQAvD_BwE&gclsrc=aw.ds)
- BI / 3. Talend – Guide complet de la Business Intelligence / https://www.tableau.com/fr-fr/learn/articles/business-intelligence
- BI / 4. SAP – Qu'est-ce que la Business Intelligence ? / https://www.talend.com/fr/resources/guide-business-intelligence/
- BI / 5. Tableau – Logiciel de Business Intelligence / https://www.sap.com/canada-fr/products/data-cloud/cloud-analytics/what-is-business-intelligence.html

### 2.1.2 Assurer la qualité et la fiabilité des analyses.

Faire le lien entre BI et gouvernance, parler de l'importance de restituer des valeurs justes sinon plus aucun sens (chose complexe) et parler de l'importance de comprendre le besoin en amont.
Que les données que nous traitons on une origine / provenance, une raison de pourquoi nous la récoltons et une finalité. Qu'il est important de maintenir cette cohérence dans l'ensemble de la chaîne et du processus afin que tous cela fonctionne. D'ou la gouvernance !

Exemple : 
Les nombreux échanges fait avec le métier afin de définir leur besoin et de le retranscrire de manière correcte en données.
Le projet de suivi des anomalies des données : TDB_QDD_DATA

Source :
- Gouvernance / 2. Talend – Gouvernance des données : principe, utilité et outils / https://www.talend.com/fr/resources/guide-gouvernance-donnees/
- Nettoyage / 1. Talend – Nettoyage des données : guide du data cleansing / https://www.talend.com/fr/resources/what-is-data-cleansing/
- Nettoyage / 2. AWS – Qu'est-ce que le nettoyage des données ? / https://aws.amazon.com/fr/what-is/data-cleansing/


### 2.1.3 Favoriser une prise de décision éclairée en limitant les incohérences. 

C'est une démarche longue et qui nécessite de la régularité à mettre en place, mais qui par la suite donnera de bonnes habitudes (cercle vertueux), un gain de temps et de justesse donc d'argent (amélioration de la qualité de la stratégie et prise de décision). 

Exemple :
Amélioration des analyses sur notre Portefeuille des adhérents lors du Comité de direction annuel grâce au développement d'une application QS et de la volonté de pousser les analyses plus loins et de donner plus la main sur les données au métier. 

Source :
- Gouvernance / 2. Talend – Gouvernance des données : principe, utilité et outils / https://www.talend.com/fr/resources/guide-gouvernance-donnees/
- Nettoyage / 1. Talend – Nettoyage des données : guide du data cleansing / https://www.talend.com/fr/resources/what-is-data-cleansing/
- Nettoyage / 2. AWS – Qu'est-ce que le nettoyage des données ? / https://aws.amazon.com/fr/what-is/data-cleansing/


## 2.2. Composants clés d'une gouvernance efficace pour la BI

### 2.2.1 Gestion de la qualité des données : exactitude, complétude, cohérence.

Parler de l'importance d'avoir des données juste et comment faire (anticipation, réflexion en amont, structure du modèle de données, pratiques de dev)

Le projet de refonte de l'outil de gestion Cleva -> réflexion sur le datawarehouse, enrichissement, controle qualité au travers de rapports bo

Source : 
- Nettoyage / 1. Talend – Nettoyage des données : guide du data cleansing / https://www.talend.com/fr/resources/what-is-data-cleansing/
- Nettoyage / 2. AWS – Qu'est-ce que le nettoyage des données ? / https://aws.amazon.com/fr/what-is/data-cleansing/


### 2.2.2 Sécurité et confidentialité des données.

Importance de sécuriser ses données, gérer les droits d'accès etc

Données autour de la santé sont hyper règlementées, les rapports nécessitent des droits d'accès en fonction du type de données.

Source :
- RGPD / 1. CNIL – Le règlement européen sur la protection des données / https://www.cnil.fr/fr/reglement-europeen-protection-donnees
- RGPD / 2. CNIL – Comprendre le RGPD / https://www.cnil.fr/fr/comprendre-le-rgpd
- RGPD / 3. Service-Public.fr – Obligations en matière de protection des données personnelles (RGPD) / https://entreprendre.service-public.fr/vosdroits/F24270
- RGPD / 4. France Num – Comment gérer les données personnelles de son entreprise en conformité avec le RGPD ? / https://www.francenum.gouv.fr/guides-et-conseils/protection-contre-les-risques/gestion-des-donnees-personnelles/comment-gerer-les

### 2.2.3 Traçabilité et compréhension des données.

Importance de versionner et commenter ses dev, les tables, les champs 

Citation de l'utilisation d'outils tel que Git hub, draw.io etc

Source :
Chercher source sur le versionning et Git Hub

### 2.2.4 Catalogage et métadonnées. 

Importance d'avoir à la fois une compréhension technique mais aussi fonctionnelle des données : par exemple être capable de retranscrire une données en fonction métier. Utilisation de métadonnées pour définir des données (voir comment développer la notion) 

Mettre en avant les outils spécialisés dans le cataloguage de données  : Data Galaxy

Source : 
- Catalogue / 1. Oracle – Qu’est-ce qu’un catalogue de données ? / https://www.oracle.com/fr/big-data/data-catalog/what-is-a-data-catalog/
- Catalogue / 2. Talend – Data catalog : définition et enjeux business / https://www.talend.com/fr/resources/guide-data-catalog/
- Catalogue / 3. INSEE – Le catalogue des données de l'Insee / https://www.insee.fr/fr/information/8184173
- Catalogue / 4. AWS – Qu'est-ce qu'un catalogue de données ? / https://aws.amazon.com/fr/what-is/data-catalog/
- Catalogue / 5. data.gouv.fr – Catalogue des données de data.gouv.fr / https://www.data.gouv.fr/fr/datasets/catalogue-des-donnees-de-data-gouv-fr/
- Catalogue / 6. Qlik – Catalogue de données / https://help.qlik.com/fr-FR/cloud-services/Subsystems/Hub/Content/Sense_Hub/LoadData/data-catalog.htm
- Chercher Data Galaxy

## 2.3. Rôles et responsabilités

### 2.3.1 Chief Data Officer (CDO), Data Steward, Data Owner.

Présenter les profils typiques des personnes garantes de la gouvernance des données.

Mettre en avant les échanges fait entre data steward, owner etc chez alptis afin de garantir des livraisons en prd péraines

Source :
- PPT Gouvernance des données Alptis
- Gouvernance / 1. Google Cloud – Qu'est-ce que la gouvernance des données ? / https://cloud.google.com/learn/what-is-data-governance?hl=fr
- Gouvernance / 2. Talend – Gouvernance des données : principe, utilité et outils / https://www.talend.com/fr/resources/guide-gouvernance-donnees/
- Gouvernance / 3. SAP – Qu'est-ce que la gouvernance des données ? / https://www.sap.com/suisse/products/data-cloud/master-data-governance/what-is-data-governance.html
- Gouvernance / 4. Oracle – Qu’est-ce que la gouvernance des données ? / https://www.oracle.com/fr/security/definition-data-governance/


### 2.3.2 Collaboration entre les équipes IT et métiers.

Parler des échanges mis en places avec le métier et l'intérêt de data galaxy

Source :
- Catalogue / 1. Oracle – Qu’est-ce qu’un catalogue de données ? / https://www.oracle.com/fr/big-data/data-catalog/what-is-a-data-catalog/
- Catalogue / 2. Talend – Data catalog : définition et enjeux business / https://www.talend.com/fr/resources/guide-data-catalog/
- Catalogue / 3. INSEE – Le catalogue des données de l'Insee / https://www.insee.fr/fr/information/8184173
- Catalogue / 4. AWS – Qu'est-ce qu'un catalogue de données ? / https://aws.amazon.com/fr/what-is/data-catalog/
- Catalogue / 5. data.gouv.fr – Catalogue des données de data.gouv.fr / https://www.data.gouv.fr/fr/datasets/catalogue-des-donnees-de-data-gouv-fr/
- Catalogue / 6. Qlik – Catalogue de données / https://help.qlik.com/fr-FR/cloud-services/Subsystems/Hub/Content/Sense_Hub/LoadData/data-catalog.htm
- Chercher Data Galaxy
- PPT Gouvernance des données Alptis
- Gouvernance / 1. Google Cloud – Qu'est-ce que la gouvernance des données ? / https://cloud.google.com/learn/what-is-data-governance?hl=fr
- Gouvernance / 2. Talend – Gouvernance des données : principe, utilité et outils / https://www.talend.com/fr/resources/guide-gouvernance-donnees/
- Gouvernance / 3. SAP – Qu'est-ce que la gouvernance des données ? / https://www.sap.com/suisse/products/data-cloud/master-data-governance/what-is-data-governance.html
- Gouvernance / 4. Oracle – Qu’est-ce que la gouvernance des données ? / https://www.oracle.com/fr/security/definition-data-governance/

### 2.3.3 Sensibilisation des utilisateurs de la donnée

l'envie de sensibiliser le métier en leur donnant la main sur des sandbox, d'être amené à manipuler la données en leur montrant les étapes de transition afin de repondre fidèlement  à leur besoin

Les pages de test et manipulation dans les applications QS

Source :
- PPT Gouvernance des données Alptis
- Gouvernance / 1. Google Cloud – Qu'est-ce que la gouvernance des données ? / https://cloud.google.com/learn/what-is-data-governance?hl=fr
- Gouvernance / 2. Talend – Gouvernance des données : principe, utilité et outils / https://www.talend.com/fr/resources/guide-gouvernance-donnees/
- Gouvernance / 3. SAP – Qu'est-ce que la gouvernance des données ? / https://www.sap.com/suisse/products/data-cloud/master-data-governance/what-is-data-governance.html
- Gouvernance / 4. Oracle – Qu’est-ce que la gouvernance des données ? / https://www.oracle.com/fr/security/definition-data-governance/
 Chercher une source intéressante pour mettre en valeur l'importance de la sensibilisation des utilisateurs



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
