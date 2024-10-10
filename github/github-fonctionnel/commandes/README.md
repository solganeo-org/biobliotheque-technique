
# Commandes et Actions principales dans GitHub Desktop 🖥️

GitHub Desktop permet d'effectuer les actions Git les plus courantes à travers une interface graphique conviviale. Ce fichier répertorie les principales actions que vous pouvez réaliser dans GitHub Desktop, avec des explications et des conseils.

---

## 📥 1. Cloner un dépôt GitHub

Cloner un dépôt permet de télécharger une copie du projet GitHub sur votre machine locale.

### Étapes :
- Cliquez sur **File** > **Clone Repository...**
- Entrez l'URL du dépôt ou sélectionnez un dépôt à partir de votre liste GitHub.

---

## 🔄 2. Synchroniser votre dépôt local avec le dépôt distant (Fetch/Pull)

Avant de commencer à travailler, assurez-vous que votre dépôt local est à jour avec le dépôt distant.

### Fetch :
- Cliquez sur **Fetch origin** pour récupérer les dernières modifications sans les appliquer à votre branche.
  
### Pull :
- Cliquez sur **Pull origin** pour récupérer et appliquer les modifications sur votre branche active.

---

## 🌿 3. Créer une nouvelle branche

Travaillez toujours sur une branche distincte pour chaque fonctionnalité ou correction de bug afin de maintenir la branche principale stable.

### Étapes :
- Allez dans **Branch** > **New Branch...**.
- Nommez la branche de manière explicite, par exemple `feature/nouvelle-fonctionnalite`.

---

## 💾 4. Faire un commit

Un commit enregistre les modifications dans l'historique du projet.

### Étapes :
- Modifiez vos fichiers dans votre éditeur de code.
- Dans GitHub Desktop, sélectionnez les fichiers modifiés.
- Ajoutez un message clair et concis dans le champ **Summary** (par exemple, `"Ajout du formulaire de contact"`).
- Cliquez sur **Commit to main** ou sur votre branche active.

---

## 🔄 5. Pousser vos commits sur GitHub (Push)

Une fois vos commits effectués, poussez-les sur GitHub pour les rendre disponibles à vos collaborateurs.

### Étapes :
- Cliquez sur **Push origin** pour envoyer vos modifications vers GitHub.

---

## 🔀 6. Fusionner une branche (Merge)

Une fois que votre branche est prête, fusionnez-la avec la branche principale.

### Étapes :
- Allez dans **Branch** > **Merge into current branch...**
- Sélectionnez la branche que vous souhaitez fusionner dans la branche active.

---

## 📑 7. Créer une Pull Request

Les Pull Requests permettent de soumettre vos modifications pour revue avant de les fusionner dans la branche principale.

### Étapes :
- Une fois que votre travail est terminé sur une branche, allez sur GitHub et cliquez sur **New Pull Request** pour commencer le processus de revue.

---

## 🚧 8. Résoudre un conflit

GitHub Desktop vous aidera à résoudre les conflits si plusieurs personnes modifient les mêmes fichiers.

### Étapes :
- GitHub Desktop signale un conflit et vous demande de résoudre les fichiers concernés.
- Ouvrez le fichier dans votre éditeur de texte et corrigez le conflit.
- Revenez dans GitHub Desktop et marquez le conflit comme résolu en cliquant sur **Mark as resolved**.

---

## 🧹 9. Supprimer une branche après fusion

Une fois qu'une branche est fusionnée, il est recommandé de la supprimer pour éviter les branches obsolètes.

### Étapes :
- Allez dans **Branch** > **Delete Branch** pour supprimer la branche locale.
- Supprimez également la branche distante sur GitHub si nécessaire.

---

## 📜 10. Revoir l'historique des commits

L'onglet **History** dans GitHub Desktop permet de revoir l'historique des commits, utile avant de pousser des changements.

### Étapes :
- Allez dans l'onglet **History** pour voir les commits récents.

---

## 🚫 11. Force Push

Évitez d'utiliser le **Force Push** à moins d'en avoir vraiment besoin, et assurez-vous d'informer les autres membres de l'équipe avant de l'utiliser.

### Étapes :
- Cochez **Force Push** dans les options de Push lorsque c'est nécessaire, mais uniquement après une concertation avec l'équipe.

---

## Conclusion 🎯

GitHub Desktop simplifie l'utilisation de Git, mais il est important de comprendre les actions essentielles pour gérer efficacement les dépôts Git. Utilisez cet outil pour collaborer, organiser et maintenir un flux de travail Git sans accroc.

---

## 📚 Ressources supplémentaires :
- [Documentation GitHub Desktop](https://docs.github.com/en/desktop)
- [Guide des Pull Requests GitHub](https://docs.github.com/en/pull-requests)