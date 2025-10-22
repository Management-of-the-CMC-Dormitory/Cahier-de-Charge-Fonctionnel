# Contraintes du projet

Le développement de l’application web **« Gestion de l’Internat du CMC Béni Mellal »** doit tenir compte de plusieurs contraintes techniques, humaines, temporelles et organisationnelles afin de garantir la réussite du projet dans les délais et avec la qualité attendue.

## A. Contraintes techniques

### 1. Architecture et technologies
- Le système doit être développé sous forme d’une application web **responsive** accessible via navigateur (Chrome, Firefox, Edge, etc.).  
- L’architecture doit permettre une **évolution future** (ajout de nouvelles fonctionnalités, intégration d’une application mobile, etc.).  
- L’application doit être conçue avec des **technologies modernes** assurant performance et sécurité (framework web, base de données relationnelle, API REST, etc.).  

### 2. Base de données
- Une **base de données centralisée et sécurisée** doit stocker toutes les informations (résidents, chambres, repas, réclamations, etc.).  
- Les accès à la base doivent être **contrôlés par des rôles et authentifiés**.  
- Les données sensibles (CIN, email, téléphone, etc.) doivent être **cryptées**.  

### 3. Sécurité
- L’accès à l’application doit se faire via un système d’**authentification sécurisé** (login/mot de passe ou token).  
- Les échanges de données doivent être protégés contre les attaques courantes (injection SQL, XSS, CSRF).  
- Les fichiers téléchargés par les utilisateurs doivent être **vérifiés et filtrés** avant stockage.  

### 4. Compatibilité et accessibilité
- L’interface doit être **responsive**, adaptée aux ordinateurs, tablettes et smartphones.  
- Le design doit respecter des **normes d’ergonomie et d’accessibilité** pour une expérience utilisateur fluide.  
- L’application doit fonctionner sur les systèmes **Windows, Linux et Android** (via navigateur).  

### 5. Performance
- Le temps de chargement des pages doit rester **inférieur à 3 secondes**.  
- Le système doit supporter **plusieurs connexions simultanées** sans ralentissement notable.  
- Les opérations critiques (authentification, recherche, enregistrement) doivent être **optimisées**.  

## B. Contraintes humaines
- L’équipe de développement est composée d’un groupe de **quatre étudiants** responsables de l’analyse, de la conception et du développement complet du système.  
- Chaque membre devra assumer un **rôle précis** (chef de projet, développeur back-end, développeur front-end, testeur, etc.).  
- Le projet sera réalisé sous la **supervision d’un formateur encadrant**, assurant le suivi pédagogique et la validation des livrables.  
- Les utilisateurs finaux (administration, résidents) devront être **formés** à l’utilisation de la plateforme avant son déploiement.  

## C. Contraintes temporelles
- Le projet doit être réalisé dans un **délai limité** fixé par le calendrier pédagogique de l’OFPPT.  
- Le développement doit suivre une **planification précise** comprenant les étapes suivantes :  
  - Étude et analyse des besoins  
  - Conception (UML, maquettes, base de données)  
  - Développement et intégration  
  - Tests et validation  
  - Rédaction du rapport et présentation finale  
- Les **retards de développement** doivent être signalés et justifiés auprès du formateur encadrant.  

## D. Contraintes organisationnelles
- Le projet doit respecter la **charte graphique et les exigences de l’établissement** (CMC Béni Mellal).  
- La documentation (cahier des charges, diagrammes, manuel utilisateur) doit être rédigée en **français clair et technique**.  
- Le code source doit être **organisé, commenté et versionné** (Git, GitHub, etc.).  
- Le déploiement doit se faire sur un **serveur local ou en hébergement web sécurisé** (selon les ressources disponibles).  
- La **maintenance et les mises à jour** devront être facilement réalisables par l’équipe technique du centre.  

## E. Contraintes de sécurité et confidentialité
- Toutes les informations personnelles (étudiants, résidents, administrateurs) doivent être **protégées** conformément aux bonnes pratiques de gestion des données.  
- Seules les **personnes autorisées** peuvent accéder aux données sensibles.  
- Les **logs d’activité** doivent être conservés pour assurer la traçabilité des actions.  

**En résumé**, ces contraintes définissent le cadre dans lequel le projet doit être développé.  
Elles garantissent la **fiabilité, la sécurité, la maintenabilité et la pérennité** de la solution finale.
