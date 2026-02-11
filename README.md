Lab 1 : Suivi des Scripts des Développeurs

     Objectif:
     
    Utiliser JDBC pour :
    
    Se connecter à MySQL
    
    Créer une base de données
    
    Insérer des données
    
    Afficher des statistiques

   1.1 création de la base de données "atelier":
   <img width="1914" height="1079" alt="Capture d&#39;écran 2026-02-10 232307" src="https://github.com/user-attachments/assets/4c7c054f-bc94-4131-afb3-44c3d9e2d6f4" />
   La base de données atelier a été créée avec succès dans MySQL.

   1.2Résultats d’exécution
   <img width="1916" height="1079" alt="Capture d&#39;écran 2026-02-11 004507" src="https://github.com/user-attachments/assets/d8bedb02-10e4-4b16-85d2-eb249e564691" />
   La console affiche :

    Le nombre maximum de scripts par jour

    Le classement des développeurs

    Le total des scripts par semaine

    Le total des scripts pour un développeur spécifique   
Lab 2 : Gestion des Machines et Employés (JDBC en Couches)
  Objectif

    Mettre en place une architecture en couches :

    DAO

    Service

    Classe de test
   2.1 Création des tables
   <img width="1918" height="1078" alt="Capture d&#39;écran 2026-02-11 005321" src="https://github.com/user-attachments/assets/e242f041-8f71-4058-87c5-e852b1bb8bec" />
   <img width="1919" height="1079" alt="Capture d&#39;écran 2026-02-11 005330" src="https://github.com/user-attachments/assets/174c06af-f581-4f3d-b0c2-00212c155fdd" />
   Les tables suivantes ont été créées :

    employe

    machine
   2.2 TestEmploye.java – Fonctionnement du programme
   <img width="1919" height="1079" alt="Capture d&#39;écran 2026-02-11 125351" src="https://github.com/user-attachments/assets/a5fb9198-2ba3-46b1-a3b8-d91a49a86aad" />
   
création 

    Un employé "Maroanin" est créé avec l’ID 1.

Lecture 

    Le programme affiche la liste des employés présents dans la base de données.

Mise à jour 

    Le poste est modifié en "Superviseur".
    Résultat : true .

Suppression 

    L’employé est supprimé avec succès.
    Résultat : true.

   2.3 TestMachine.java – Relation Machine / Employé
   <img width="1917" height="1078" alt="Capture d&#39;écran 2026-02-11 125403" src="https://github.com/user-attachments/assets/07d793b2-36de-4530-a2d2-326685de915c" />
Cela prouve que :

    La machine est bien enregistrée

    La relation avec l’employé fonctionne

    Le programme récupère les données des deux tables

    La jointure est correctement implémentée.
   
   




  
   
