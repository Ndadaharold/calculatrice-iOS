 documentation complète , étape par étape, pour :
	1.	Créer une calculatrice iOS (style Apple) en HTML, CSS, JavaScript
	2.	La publier sur GitHub via GitHub Pages

⸻

1. Conception d’une calculatrice iOS (HTML/CSS/JavaScript)

A. Objectif du projet

Créer une calculatrice qui ressemble à celle de l’iPhone (design et fonctionnalités) en utilisant uniquement HTML, CSS et JavaScript.

⸻

B. Structure générale du projet
	•	Fichier HTML : structure de la calculatrice (écran, boutons, etc.)
	•	Fichier CSS : style visuel (couleurs, ombrage, polices, responsive)
	•	Fichier JavaScript : logique de calcul (opérations, affichage, gestion des erreurs)

⸻

C. Fonctionnalités principales à coder
	•	Écran d’affichage
	•	Boutons (0-9, ., +, −, ×, ÷, =, AC, DEL)
	•	Gestion du clavier tactile
	•	Calcul dynamique (sans recharger la page)
	•	Affichage en temps réel
	•	Fonctionnalités bonus possibles :
	•	Mode sombre/clair
	•	Historique des opérations
	•	Responsive (fonctionne sur mobile/tablette)

⸻

D. Étapes de développement
	1.	Créer le fichier index.html
	•	Ajouter une section d’affichage (div)
	•	Ajouter les boutons de la calculatrice (dans une grid)
	2.	Créer le fichier style.css
	•	Importer une police similaire à celle d’iOS
	•	Appliquer un style en grid pour les boutons
	•	Ajouter des effets visuels (ombres, bordures arrondies, etc.)
	3.	Créer le fichier script.js
	•	Ajouter des événements click pour chaque bouton
	•	Créer une fonction pour afficher les chiffres et les opérations
	•	Gérer la logique du bouton = (évaluation de l’expression)
	•	Ajouter les fonctions AC (reset) et DEL (supprimer un caractère)

⸻

E. Astuces pour un style iOS
	•	Utilise des couleurs douces : gris foncé, orange, blanc
	•	Bordures arrondies et ombres douces
	•	Responsive grid avec display: grid
	•	Animation au clic sur les boutons (effet pressé)

⸻

2. Publier le projet sur GitHub

A. Étapes pour push un projet sur GitHub (via GitHub Desktop ou terminal)

⸻

Étape 1 : Créer un compte GitHub
	•	Va sur https://github.com
	•	Crée un compte (si ce n’est pas déjà fait)

⸻

Étape 2 : Créer un nouveau dépôt
	•	Clique sur “New repository”
	•	Donne-lui un nom (ex: calculatrice-ios)
	•	Coche la case “Add a README” (facultatif)
	•	Clique sur “Create repository”

⸻

Étape 3 : Préparer ton projet en local

Dans ton dossier local (où il y a index.html, style.css, script.js) :

Si tu utilises GitHub Desktop :
	•	Clique sur “Add local repository”
	•	Sélectionne ton dossier
	•	Clique sur “Publish repository”

Si tu utilises le terminal (Git) :

cd ton-dossier
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/ton-nom/calculatrice-ios.git
git push -u origin main



⸻

Étape 4 : Activer GitHub Pages
	1.	Va dans ton dépôt GitHub
	2.	Clique sur “Settings”
	3.	Dans la section “Pages” (barre latérale gauche) :
	•	Source : choisis la branche main
	•	Dossier : / (root)
	•	Clique sur “Save”

GitHub générera un lien comme :

https://ton-nom.github.io/calculatrice-ios/



⸻

B. Tester le lien
	•	Ouvre le lien dans un navigateur
	•	La calculatrice devrait s’afficher comme une app iOS

⸻

3. Astuce bonus

Pour t’entraîner, essaie de :
	•	Reproduire le mode sombre automatique selon les préférences du navigateur
	•	Ajouter un effet haptique (visuel) au clic
	•	Améliorer l’UI avec Figma avant de coder

⸻

