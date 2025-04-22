documentation  des deux méthodes principales pour push des projets sur GitHub :

⸻

DOC OFFICIELLE ULTRA DÉTAILLÉE

“Comment publier un projet sur GitHub”

Par Ndada Harold Perin

⸻

Méthode 1 : Upload Manuel (Interface Web - sans terminal, sans Git)

Utilisation :

Simple, rapide, idéale pour les débutants, ou pour un upload rapide sans installer Git.

⸻

Étapes détaillées :

1. Créer un compte GitHub
	•	Va sur : https://github.com
	•	Clique sur Sign Up
	•	Suis les étapes pour créer un compte

⸻

2. Créer un nouveau dépôt
	1.	Clique sur le bouton “+” en haut à droite > New repository
	2.	Remplis :
	•	Repository name : ex. calculatrice-ios
	•	Description : “Une calculatrice iOS moderne en HTML/CSS/JS”
	•	Visibilité : coche Public
	•	Options : coche Add a README
	3.	Clique sur Create repository

⸻

3. Ajouter tes fichiers manuellement
	1.	Clique sur “Add file” > “Upload files”
	2.	Glisse-dépose les fichiers de ton projet (index.html, style.css, script.js, etc.)
	3.	En bas :
	•	Dans “Commit changes”, écris un message (ex. “Ajout initial du projet”)
	•	Clique sur Commit changes

⸻

4. (Optionnel) Activer GitHub Pages pour mettre ton site en ligne
	1.	Va dans Settings > Pages
	2.	Dans “Source” :
	•	Branche : main
	•	Dossier : /root
	3.	Clique sur Save
	4.	GitHub te génère un lien :
https://ton-nom-utilisateur.github.io/nom-du-repo/

⸻

5. Résultat
	•	Code source visible : https://github.com/ton-utilisateur/ton-projet
	•	Projet en ligne : https://ton-utilisateur.github.io/ton-projet/

⸻

Méthode 2 : Utilisation de Git + Terminal (push classique)

Utilisation :

Professionnelle, recommandée pour développeurs réguliers, ou pour synchroniser ton code à distance.

⸻

Prérequis :
	•	Git installé : https://git-scm.com/downloads
	•	Un projet existant (HTML, CSS, JS…)
	•	Un compte GitHub actif

⸻

Étapes détaillées :

1. Créer un dépôt GitHub

Identique à la méthode 1 (voir plus haut)

⸻

2. Ouvrir le terminal et se rendre dans le dossier du projet

cd chemin/vers/ton/projet



⸻

3. Initialiser le projet Git localement

git init



⸻

4. Ajouter les fichiers à Git

git add .



⸻

5. Faire un commit

git commit -m "Premier commit de mon projet"



⸻

6. Lier le dépôt local au dépôt distant GitHub

git remote add origin https://github.com/ton-utilisateur/ton-repo.git



⸻

7. Pousser (push) le projet vers GitHub

git branch -M main
git push -u origin main

8. (Optionnel) Activer GitHub Pages

Voir méthode 1, étape 4.

⸻

9. Résultat
	•	Code source sur GitHub : https://github.com/ton-utilisateur/ton-repo
	•	Site en ligne via GitHub Pages : https://ton-utilisateur.github.io/ton-repo/

Comparatif rapide des deux méthodes

Critère	Méthode 1 (Web)	Méthode 2 (Git)
Installation	Aucune	Nécessite Git
Facilité	Très facile	Moyen à avancé
Vitesse	Plus lente pour gros projets	Très rapide
Utilisation pro	Non recommandée	Recommandée
Contrôle des versions	Limité	Complet avec historique Git
Collaboratif	Moins pratique	Idéal pour travail d’équipe

