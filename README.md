📊 Projet : Suivi de Projet SFR - Google Sheets Automatisé


🔹 Description


J'ai créé un tableau de suivi sur Google Sheets pour gérer différents projets de SFR. Ce tableau inclut des automatisations via VBA et Google Apps Script pour améliorer l'efficacité du suivi.

🔹 Fonctionnalités principales

✅ Remplissage automatique du type de CAFM :



Lorsqu'un utilisateur saisit un secteur de projet, le type de CAFM est généré automatiquement grâce à un script VBA.
✅ Mise en forme conditionnelle avancée :



Un script Google Apps Script applique une mise en forme conditionnelle spécifique en fonction des étapes du projet (ex : "EN COURS", "BLOQUÉ", "Dépose drop" , "dépose axis " etc.)



C'est-à-dire que lorsque l'utilisateur choisit 'Déposé Drop', les cellules de B jusqu'à K se colorient en violet, et lorsque l'utilisateur choisit 'En cours', les cellules de B jusqu'à K se colorient en beige

🔹 Technologies utilisées

📝 Google Sheets
📌 VBA (pour l'automatisation des champs)
🖥️ Google Apps Script (pour la mise en forme conditionnelle)


![image](https://github.com/user-attachments/assets/5a8360fc-a5ca-4556-8e41-f87478588cbd)


Description du script mettreEnFormeSuiviProjet


Ce script est un Google Apps Script qui applique une mise en forme conditionnelle à une feuille Google Sheets. Il modifie automatiquement l'arrière-plan des cellules d'une plage donnée (B2:K100) en fonction de la valeur de la colonne J (statut du projet)


📌 Ce que fait ce script :


✅ Applique une mise en forme conditionnelle en fonction du statut d'un projet.
✅ Change la couleur des cellules pour mieux visualiser les différents états.
✅ Affecte la mise en forme à une plage spécifique (B2:K100).

📌 Ce qu'on peut améliorer :


🔹 Adapter la plage automatiquement en fonction du nombre de lignes.



🔹 Éviter les doublons en supprimant les anciennes règles avant d'ajouter les nouvelles.




![image](https://github.com/user-attachments/assets/e0b91966-f577-4dac-936a-b7e77855ed79)





![image](https://github.com/user-attachments/assets/96c87d29-2116-4d49-82e6-5ecdb74a777a)






