# Evaluation de Laravel
🕒 Modalités d'Évaluation

Durée : 40 minutes (Strict).

Contexte : Live Coding (L'apprenant code projetté au tableau devant le formateur).

Objectif : Valider les acquis de base Laravel (Route, Controller, Migration, Model, Blade).

📝 Cahier des Charges Commun (Pour tous les sujets)
L'application est une simple Liste d'objets (Pattern "Todo List"). L'apprenant doit implémenter les fonctionnalités suivantes :

Architecture BDD :
Création de la Migration (Table + 2 champs minimum).
Création du Model.
Création d'un Seeder (Insérer 5 fausses données).
Lecture (Read) :
Route / ou /objets.
Controller index().
Vue Blade : Affichage de la liste dans un tableau ou des cartes.
Écriture (Create) :
Formulaire simple en haut de page.
Route POST.
Controller store() avec Validation (required).
Suppression (Delete) :
Bouton "Supprimer" à côté de chaque objet.
Route DELETE.
Controller destroy().
🎲 Les 20 Variantes (Sujets)
Chaque apprenant tire un sujet au sort. La logique est identique, seul le Contexte Métier change.

1. 📝 Tâches (To-Do List Classique)
Classe : Task
Champs : title (string), is_done (boolean, default false).
Scénario : Une liste de tâches à faire pour la journée.
2. 🛒 Courses (Shopping List)
Classe : Product
Champs : name (string), quantity (integer).
Scénario : Une liste d'articles à acheter au supermarché.
3. 🎬 Films à voir (Watchlist)
Classe : Movie
Champs : title (string), director (string).
Scénario : Une liste de films que je veux regarder ce week-end.
4. 📚 Livres (Reading List)
Classe : Book
Champs : title (string), author (string).
Scénario : Une bibliothèque des livres lus ou à lire.
5. 👥 Invités (Guest List)
Classe : Guest
Champs : name (string), status (string: 'confirmé', 'en attente').
Scénario : Gérer la liste des invités pour un mariage ou une fête.
6. 🐞 Bugs (Issue Tracker)
Classe : Issue
Champs : description (text), severity (string: 'low', 'critical').
Scénario : Un mini-outil pour noter les bugs trouvés dans un projet.
7. 💡 Idées (Brainstorming)
Classe : Idea
Champs : title (string), category (string: 'App', 'Business', 'Art').
Scénario : Une boîte à idées pour noter des concepts de projets.
8. 📞 Contacts (Répertoire)
Classe : Contact
Champs : name (string), phone_number (string).
Scénario : Un carnet d'adresses minimaliste d'urgence.
9. 🎵 Musiques (Playlist)
Classe : Song
Champs : title (string), artist (string).
Scénario : Créer une playlist de favoris pour une soirée.
10. 📅 Rendez-vous (Agenda)
Classe : Appointment
Champs : client_name (string), appointment_time (datetime).
Scénario : Liste des RDV de la journée pour un coiffeur ou un médecin.
11. 📝 Notes (Memo)
Classe : Note
Champs : content (text), color (string: 'yellow', 'blue').
Scénario : Des post-its virtuels rapides.
12. 🎯 Objectifs (Goals)
Classe : Goal
Champs : description (string), deadline (date).
Scénario : Liste des résolutions pour l'année.
13. 💶 Dépenses (Expense Tracker)
Classe : Expense
Champs : label (string), amount (decimal).
Scénario : Noter ses dépenses du jour pour suivre son budget.
14. 🔗 Favoris (Bookmarks)
Classe : Bookmark
Champs : url (string), description (string).
Scénario : Sauvegarder des liens web intéressants à lire plus tard.
15. 🛠️ Compétences (Skills)
Classe : Skill
Champs : name (string), level (integer: 1-5).
Scénario : Liste des compétences acquises par un développeur.
16. 📦 Inventaire (Stock)
Classe : Item
Champs : reference (string), stock_count (integer).
Scénario : Gestion de stock simple pour un magasin.
17. 🎓 Étudiants (Présence)
Classe : Student
Champs : full_name (string), is_present (boolean).
Scénario : Faire l'appel de la classe ce matin.
18. 💬 Citations (Quotes)
Classe : Quote
Champs : text (text), author_name (string).
Scénario : Recueil de citations inspirantes.
19. 🥗 Ingrédients (Recipe)
Classe : Ingredient
Champs : name (string), quantity (string: '200g', '1L').
Scénario : Préparer les ingrédients nécessaires pour une recette de cuisine.
20. 🏆 Scores (Leaderboard)
Classe : Score
Champs : player_name (string), points (integer).
Scénario : Tableau des scores pour un tournoi de jeux vidéo.
