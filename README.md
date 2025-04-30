# TSSR-2411-P2-G1

**Projet Script**

 ![debian-12 small](https://github.com/user-attachments/assets/06d1e488-fcc1-4d70-9ba8-ea322695e98a)![microsoft-windows-server-20225184 small](https://github.com/user-attachments/assets/af86e8a1-de24-4946-b7fe-11f0b8386d58)

---
# **Présentation du Projet**

Le projet consiste à créer un script qui s’exécute sur une machine et effectue des tâches sur des machines distantes.
L’ensemble des machines sont sur le même réseau.

Les tâches sont des actions ou des requêtes d’information.

## **Objectif Principal**  🥅

-  Depuis Windows Server 2022, on exécute un script sous PowerShell 7.4 qui cible des ordinateurs Windows.

-  Depuis un serveur Debian 12, on exécute un script shell qui cible des ordinateurs Ubuntu.

---
## Objectif secondaire  🎯

-  Depuis un serveur, cibler une machine cliente avec un type d’OS différent


---
# **Introduction et mise en contexte**

Le script pour Windows doit s'exécuter sous PowerShell Core dernière version LTS, soit à cette date la 7.4 et peut avoir plusieurs dépendances de fichiers.

Le script pour Linux doit s'exécuter sur Debian 12 et utiliser les commandes et instructions shell bash et peut avoir plusieurs dépendances de fichiers

A l’exécution des 2 scripts, un menu s’affiche, il propose une navigation ergonomique avec des sous-menus dans lesquels l’utilisateur choisit l'option dont il a besoin.

Les scripts permettent de cibler soit un ordinateur soit un utilisateur. 

Récupérer et afficher le contenu des fichiers de journalisation.


---
# **Choix techniques** 💻

**Pour Windows :**

Un client Windows 10

Un Windows server 2022

**Pour Linux :**

Un client Ubuntu 22.04/24.04 LTS

Un serveur Debian 12


---
# ** Difficultés rencontrées**

Activation de la connexion à distance sous Windows


---
# ** Solutions trouvées

Connexion SSH réussi au client Windows 10

---
# **Suggestions d'améliorations possibles**
 




  
  
