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
<img width="1916" height="1073" alt="Capture d&#39;écran 2026-02-11 210942" src="https://github.com/user-attachments/assets/c9bbbf9a-f4c7-4cb4-8a64-bf881e992588" />
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
<img width="1919" height="1079" alt="Capture d&#39;écran 2026-02-11 211037" src="https://github.com/user-attachments/assets/4fbe2bfd-c600-4b2f-b058-a424f12d829c" />
   

   2.3 TestMachine.java – Relation Machine / Employé
<img width="1919" height="1079" alt="Capture d&#39;écran 2026-02-11 211108" src="https://github.com/user-attachments/assets/07cef7dd-cbad-4483-927a-3bc05a358de7" />
Cela prouve que :

    La machine est bien enregistrée

    La relation avec l’employé fonctionne

    Le programme récupère les données des deux tables

    La jointure est correctement implémentée.
   
   




  
   
