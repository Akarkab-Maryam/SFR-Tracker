📊 Projet : Suivi de Projet SFR - Google Sheets Automatisé


🔹 Description


J'ai créé un tableau de suivi sur Google Sheets pour gérer différents projets de SFR. Ce tableau inclut des automatisations via VBA et Google Apps Script pour améliorer l'efficacité du suivi.

🔹 Fonctionnalités principales

✅ Remplissage automatique du type de CAFM :



Lorsqu'un utilisateur saisit un secteur de projet, le type de CAFM est généré automatiquement grâce à un script VBA.
✅ Mise en forme conditionnelle avancée :



Un script Google Apps Script applique une mise en forme conditionnelle spécifique en fonction des étapes du projet (ex : "EN COURS", "BLOQUÉ", etc.)



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








