Évaluation Laravel – Live Coding
🕒 Modalités d’évaluation
Durée : 40 minutes (strict)

Format : Live Coding (L’apprenant code en direct, projeté au tableau, devant le formateur)

Objectif pédagogique : Valider les acquis fondamentaux de Laravel :

Routes
Controllers
Migrations
Models
Blade (vues)
📝 Cahier des charges commun
(Applicable à tous les sujets)

L’application à réaliser est une liste d’objets suivant le pattern Todo List.

1. Architecture Base de Données
Création d’une migration

Une table
Minimum 2 champs
Création du Model associé

Création d’un Seeder

Insertion de 5 données factices
2. Lecture (Read)
Route : / ou /objets

Méthode Controller : index()

Vue Blade :

Affichage de la liste
Format libre : tableau ou cartes
3. Création (Create)
Formulaire simple (en haut de page)

Route : POST

Méthode Controller : store()

Validation :

Champs requis (required)
4. Suppression (Delete)
Bouton "Supprimer" pour chaque élément
Route : DELETE
Méthode Controller : destroy()
🎲 Sujets (20 variantes)
Chaque apprenant tire un sujet au sort. La logique technique reste identique, seul le contexte métier change.

1. 📝 Tâches (To-Do List)
Classe : Task

Champs :

title (string)
is_done (boolean, default: false)
Scénario : Liste de tâches à faire dans la journée

2. 🛒 Courses (Shopping List)
Classe : Product

Champs :

name (string)
quantity (integer)
Scénario : Articles à acheter au supermarché

3. 🎬 Films à voir (Watchlist)
Classe : Movie

Champs :

title (string)
director (string)
Scénario : Films à regarder le week-end

4. 📚 Livres (Reading List)
Classe : Book

Champs :

title (string)
author (string)
Scénario : Livres lus ou à lire

5. 👥 Invités (Guest List)
Classe : Guest

Champs :

name (string)
status (string : confirmé, en attente)
Scénario : Liste d’invités pour un événement

6. 🐞 Bugs (Issue Tracker)
Classe : Issue

Champs :

description (text)
severity (string : low, critical)
Scénario : Suivi de bugs d’un projet

7. 💡 Idées (Brainstorming)
Classe : Idea

Champs :

title (string)
category (string : App, Business, Art)
Scénario : Boîte à idées de projets

8. 📞 Contacts (Répertoire)
Classe : Contact

Champs :

name (string)
phone_number (string)
Scénario : Carnet d’adresses minimaliste

9. 🎵 Musiques (Playlist)
Classe : Song

Champs :

title (string)
artist (string)
Scénario : Playlist de favoris

10. 📅 Rendez-vous (Agenda)
Classe : Appointment

Champs :

client_name (string)
appointment_time (datetime)
Scénario : RDV quotidiens (médecin, coiffeur)

11. 📝 Notes (Memo)
Classe : Note

Champs :

content (text)
color (string : yellow, blue)
Scénario : Post-its virtuels

12. 🎯 Objectifs (Goals)
Classe : Goal

Champs :

description (string)
deadline (date)
Scénario : Résolutions annuelles

13. 💶 Dépenses (Expense Tracker)
Classe : Expense

Champs :

label (string)
amount (decimal)
Scénario : Suivi du budget quotidien

14. 🔗 Favoris (Bookmarks)
Classe : Bookmark

Champs :

url (string)
description (string)
Scénario : Liens à lire plus tard

15. 🛠️ Compétences (Skills)
Classe : Skill

Champs :

name (string)
level (integer : 1–5)
Scénario : Compétences d’un développeur

16. 📦 Inventaire (Stock)
Classe : Item

Champs :

reference (string)
stock_count (integer)
Scénario : Gestion de stock simple

17. 🎓 Étudiants (Présence)
Classe : Student

Champs :

full_name (string)
is_present (boolean)
Scénario : Appel en classe

18. 💬 Citations (Quotes)
Classe : Quote

Champs :

text (text)
author_name (string)
Scénario : Citations inspirantes

19. 🥗 Ingrédients (Recette)
Classe : Ingredient

Champs :

name (string)
quantity (string : 200g, 1L)
Scénario : Préparation d’une recette

20. 🏆 Scores (Leaderboard)
Classe : Score

Champs :

player_name (string)
points (integer)
Scénario : Classement de tournoi