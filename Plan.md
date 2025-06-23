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

Parler des échanges mis en places avec le métier et l'intérêt de data galaxy, de l'intérêt de définir un BA sur chaque projet et responsable des projets livrés côté métier. 

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
Montrer que la gouvernance ne repose pas uniquement sur des procédures constantes. Il est important de la faire constamment évoluer notamment en fonction de la stratégie de son entreprise.

### 3.1.1 Élaboration de politiques de gouvernance alignées sur les objectifs stratégiques.
Voir quelles sont les politiques et la stratégie qu'Alptis souhaiterai mettre en place par la suite. Comment adapter cette gouvernance ? Est ce que Cleva joue sur cette stratégie ? Et l'IA ?
Exemple : Refonte de la stratégie de l'équipe data suite au départ de certains membres et suppression du groupe de maintenance. Objectif de demain mettre cleva en prod. Stratégie ?

Lien avec les OKR / KPI globaux de l’entreprise : par exemple, si Alptis veut améliorer la satisfaction client ou la productivité des équipes, comment la gouvernance peut y contribuer ?

Impact de l’IA générative et de Cleva sur la stratégie Data :

Peut-être expliquer que Cleva est un outil cœur de gestion, donc la qualité et structuration des données est vitale avant sa mise en production.

Pour l’IA, évoquer que des usages futurs (modèles prédictifs, copilotes internes) nécessitent une excellente traçabilité et qualité des données sources.

Tu peux citer AXA XL comme modèle d’entreprise où la stratégie est incarnée dans un CoE piloté au plus haut niveau (C-level).

Souligne la stratégie Data Academy pour acculturer les métiers.

### 3.1.2 Définition de standards et de processus pour la gestion des données. 
Parler des processus définis par l'équipe dans la mise en place de la gouvernance au sein de l'équipe. Voir le PPT Gouvernance
Donner l'exemple avec le Qlik Community pour uniformiser toutes nos application QS selon une même charte graphique et mise en forme des pages.

Ajouter que la mise en place de standards (ex. Qlik Community) réduit les coûts de maintenance et facilite l’onboarding des nouveaux arrivants.

onner un exemple visuel si possible dans les annexes (charte type de dashboard ?).

### 3.1.3 Sensibilisation des collaborateurs à l'importance de la gouvernance des données.
Travail avec les équipes comme le RSE ou digital Bar afin de créer des programme de sensibilisation aux technologies et rôle de la Data
Souder les équipes, faire remonter les chiffres aux entièreté des équipes via le chiosque afin que tout le monde ai une vision claire de l'entreprise.

Ajouter que cette culture commune autour de la donnée aide à mieux détecter les incohérences au quotidien (effet qualité continue).

Ajouter une citation ou une illustration d’atelier/rencontre menée (même simple) avec le Digital Bar, ou un retour utilisateur si tu en as.



## 3.2. Adoption d'outils et technologies

### 3.2.1 Utilisation de solutions de gestion de la qualité des données, de catalogues de données, de plateformes de gouvernance.
Parler du besoin de faire évoluer ses outils : Passage de Oracle -> Snowflake car avantage de solution cloud donc plus efficace et mieux sécurisé.
Parfois contraint ex de Talend qui se veut de plus en plus couteux et donc qu'on souhaite délaisser. 

Mettre en avant le rôle de DataGalaxy comme outil de capitalisation (évite la perte de connaissance lors des départs).

Évoquer des outils en veille comme Ataccama, Collibra, Informatica, même si non utilisés chez vous, pour montrer que tu connais l’écosystème.

Mentionne Doctolib avec ses certifications ISO 27701/27017/27018 et l’usage de dbt pour illustrer la structuration et la fiabilité technique.

Évoque la stack technique (Catalog, Quality, BI) à travers Doctolib.

### 3.2.2 Intégration avec les outils BI existants. 
Parler du choix de ces outils et de la raison pour laquelle on les choisis. Qu'il est important d'avoir une certaine compatibilité entre les différents outils et qu'il n'est pas nécessaire d'avoir plusieurs outils similaires
Définir le rôle précis de l'outil que l'on utilise. Montrer qu'il est aussi très difficile pour une entreprise de tout changer car cela impacte les habitudes et tout le travail réalisé en amont.

Bien préciser la complémentarité (et non la redondance) entre :

BusinessObjects → diffusion automatique / rapports normés

Qlik Sense → exploration dynamique / autonomie métier

Tu peux illustrer avec un tableau comparatif simple.


## 3.3. Conformité réglementaire

### 3.3.1 Respect des réglementations en vigueur : RGPD, Data Governance Act.
Constamment s'assurer de respecter la réglementation vis à vis du traitement des données
Cas avec Google Analytics -> Matomo car google n'était plus reconnu comme un outil réglementaire et matomo est français.

Définir brièvement le Data Governance Act : obligation de partage contrôlé de la donnée au niveau européen, rôle des intermédiateurs, etc.

Expliquer que la conformité ne s’arrête pas à la collecte mais touche aussi à l’accessibilité, la documentation et l’auditabilité des données.

### 3.3.2 Mise en place de mécanismes de contrôle et d'audit.
Il est important de développer constamment des outils qui nous permettrons de contrôler plus efficacement la qualité des données et permettant d'assurer une certaine rigueur dans l'entreprise.

Le rapport BO de suivi des anomalies est une très bonne pratique → mets-le clairement ici comme mécanisme d’audit automatisé.

Ajouter que des outils comme GitHub (pour les flux Talend) permettent aussi un audit technique des changements, au niveau code.

Intègre l’exemple de SNCF Réseau comme cas de référentiel unique (Data Repository) interfacé à des PPM standardisés, illustrant l’auditabilité et la fiabilité à large échelle.


# Conclusion
Synthèse : Récapitulation des procédures et initiatives essentielles pour une gouvernance efficace des données massives au service de la BI.

Limites : Contraintes identifiées lors de l'étude.

Perspectives : Évolutions futures de la gouvernance des données avec l'émergence de nouvelles technologies et réglementations.

# Bibliographie
Sélection d'ouvrages, articles académiques, rapports d'experts et sources en ligne pertinents.


# Notes référence partie 3 :

1. AXA XL – Data Governance & Data Academy 🏦
Mise en place d’un Centre d’Excellence Data (CoE) piloté par un Chief Data Officer, qui intègre gouvernance, qualité, catalogage et traçabilité en une vision unifiée via Collibra 


Acculturation forte : création d’une Data Academy avec plus de 800 000 £ investis pour former des employés à la Data Analytics (54 apprentis) et fournir des « data champions » internes 

Résultat : montée en compétences transverse et esprit de culture data-first, avec responsabilisation des métiers via un glossaire et une plateforme collaborative.

2. Doctolib – Gouvernance robuste & sécurité certifiée
Politique data transparente : dès sa création, Doctolib applique une politique conforme RGPD/Law Informatique et Libertés, clairement expliquée via infographie 

Certifications ISO : ISO 27701 (gestion de la vie privée) renouvelée en France, Italie et Allemagne, complétée par ISO 27017/27018 pour la sécurité cloud 


Organisation Analytics Engineering : structuration de l’équipe Data, adoption de dbt, approche self-service pour améliorer la gouvernance technique et la montée en agilité 

3. SNCF Réseau – Intégration de la gouvernance dans la transformation
Digital & Gouvernance intégrées via le programme “Nouvel’R” : centralisation dans un Data Repository interfacé aux outils existants pour fiabiliser les données de projets et investissements 



Standardisation et auditabilité : adoption d’un processus PPM unifié, réduction des silos Excel, meilleurs suivis, et suivi rigoureux des changements.

➕ Ce que ces benchmarks apportent à ton mémoire
AXA XL : un modèle complet alliant institutionnalisation (CoE), culture (Data Academy) et transparence des données enterprise-wide.

Doctolib : combinaison d’une gouvernance efficace, de certifications internationales et d’une architecture technique moderne.

SNCF Réseau : exemple d’industrialisation de la gouvernance via des référentiels partagés, processus centralisés, et pilotage de la qualité.
