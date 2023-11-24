
# Cahier des charges pour le projet de site web de gestion d'école


**1. Introduction**

**1.1 Problématique**

Le projet a pour objectif de concevoir et développer un site web de gestion d'école visant à simplifier les processus administratifs, faciliter l'inscription des étudiants, gérer les cours de manière efficace, permettre un suivi précis des résultats académiques, ainsi que gérer les absences et retards.

**1.2 Objectif du projet**

Le projet a pour objectif de concevoir et développer un site web de gestion d'école visant à simplifier les processus administratifs, faciliter l'inscription des étudiants, gérer les cours de manière efficace, permettre un suivi précis des résultats académiques, ainsi que gérer les absences et retards.

**1.3Portée du projet**

La portée du projet englobe les fonctionnalités fondamentales, y compris l'inscription des étudiants, la gestion des cours, l'enregistrement des résultats, la consultation des informations personnelles, la gestion des absences et retards des étudiants .

**2. Fonctionnalités du site web**

**2.1 Inscription des étudiants**

- Mise en place d'un formulaire d'inscription comprenant les informations de base (nom, prénom, adresse, date de naissance, etc.).
- Implémentation d'un mécanisme de confirmation automatique de l'inscription par e-mail pour assurer la validité des inscriptions.

**2.2 Gestion des cours**

- Affichage d'une liste complète des cours disponibles avec des détails pertinents tels que le nom du cours, le responsable du cours, la salle de classe, les horaires, etc.

**2.3 Résultats académiques**

- Permettre aux enseignants d'enregistrer les résultats des examens dans la base de données.
- Offrir aux étudiants la possibilité de consulter leurs résultats de manière sécurisée.

**2.4 Gestion des Absences et Retards**

- Permettre aux enseignants de saisir les absences et retards des étudiants pour chaque cours.
- Mettre en place un mécanisme de notification automatique aux parents en cas d'absence ou de retard fréquent.

**2.5 Profils utilisateur**

- Création de profils distincts pour les étudiants, les enseignants, et les parents avec des informations de base.
- Intégration d'une fonction de mise à jour des informations personnelles pour permettre aux utilisateurs de maintenir des profils à jour.

**3. Exigences techniques**

**3.1 Langages de programmation**

Le développement du site web se fera en utilisant les langages suivants :
- HTML pour la structure des pages web.
- CSS pour le style et la mise en forme (bootstrap/tailwind).
- JavaScript pour les fonctionnalités interactives côté client (vue js).
- PHP pour le traitement côté serveur (Laravel).

**3.2 Base de données**

- Utilisation d'une base de données MySQL pour stocker de manière sécurisée les informations des utilisateurs, des cours, des résultats académiques, des absences et retards.
- Mise en place d'un schéma de base de données bien structuré et optimisé pour assurer la gestion efficace des données.
# Les histoires des utilisateurs
**User Stories pour les Étudiants :**

1. **En tant qu'étudiant, je veux pouvoir m'inscrire facilement en fournissant mes informations de base via un formulaire en ligne.**
   - Cela comprend des champs tels que le nom, le prénom, la date de naissance, l'adresse, etc.

2. **En tant qu'étudiant, je veux recevoir une confirmation automatique de mon inscription par e-mail pour assurer que mon processus d'inscription est complet et validé.**

3. **En tant qu'étudiant, je souhaite pouvoir consulter facilement la liste complète des cours disponibles, avec des détails sur chaque cours, tels que le nom du cours, l'enseignant, les horaires, etc.**

4. **En tant qu'étudiant, je veux pouvoir consulter mes résultats académiques de manière sécurisée et conviviale.**

5. **En tant qu'étudiant, j'aimerais avoir un profil personnel où je peux mettre à jour mes informations personnelles, comme mon adresse ou mon numéro de téléphone.**

**User Stories pour les Enseignants :**

1. **En tant qu'enseignant, je veux pouvoir enregistrer les résultats des examens de manière facile et efficace pour assurer une gestion rapide des notes.**

2. **En tant qu'enseignant, je souhaite avoir accès à une liste complète des étudiants, avec des détails pertinents sur chacun d'eux.**

3. **En tant qu'enseignant, je veux pouvoir mettre à jour mes propres informations professionnelles, telles que mon adresse e-mail ou mon numéro de téléphone, via mon profil utilisateur.**

4. **En tant qu'enseignant, j'aimerais recevoir des notifications automatiques pour les événements importants, tels que les nouvelles inscriptions ou les mises à jour de cours.**

5. **En tant qu'enseignant, je souhaite avoir un accès facile aux statistiques de performance des étudiants dans mes cours pour pouvoir ajuster mon enseignement si nécessaire.**

6. **En tant qu'enseignant, je veux pouvoir gérer et consulter les informations sur les absences et les retards des étudiants de manière centralisée.**

**User Stories pour les Parents :**

1. **En tant que parent, je veux pouvoir consulter les résultats académiques de mon enfant de manière simple et accessible.**

2. **En tant que parent, je souhaite recevoir des notifications automatiques pour les événements importants liés à la scolarité de mon enfant, tels que les réunions de parents ou les annonces de nouveaux cours.**

3. **En tant que parent, je veux avoir accès aux informations de base sur les enseignants de mon enfant, y compris leurs coordonnées, via le profil de mon enfant sur le site web.**

4. **En tant que parent, je veux pouvoir mettre à jour les informations de contact et d'urgence liées à mon enfant via le site web de l'école.**

5. **En tant que parent, je souhaite recevoir des rapports réguliers sur la performance académique de mon enfant, y compris ses notes et ses commentaires des enseignants.**

6. **En tant que parent, je veux être informé des absences et retards de mon enfant et recevoir des détails sur ces incidents.**
