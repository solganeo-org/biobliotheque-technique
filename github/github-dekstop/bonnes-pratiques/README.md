
# Bonnes pratiques Git avec GitHub Desktop 🖥️

GitHub Desktop est un excellent outil pour simplifier l'utilisation de Git avec une interface graphique conviviale. Cependant, même avec une interface simple, il est important de suivre certaines bonnes pratiques pour garantir un workflow Git propre et éviter les conflits.

---

## 1. **Toujours synchroniser avant de commencer à travailler** 🔄

Avant de commencer à travailler sur un projet, assurez-vous de **synchroniser** votre dépôt local avec le dépôt distant. Cela garantit que vous disposez des dernières modifications avant de faire des changements.

### Étapes :
- Cliquez sur **Fetch origin** pour récupérer les dernières modifications du dépôt distant.
- Ensuite, **Pull origin** pour intégrer ces modifications à votre dépôt local.

---

## 2. **Créer une branche pour chaque fonctionnalité ou correction** 🌿

Ne travaillez pas directement sur la branche `main` ou `master`. Utilisez des **branches de fonctionnalité** pour chaque nouvelle fonctionnalité ou correction de bug.

### Étapes :
- Allez dans **Branch** > **New Branch...**.
- Donnez un nom explicite à la branche comme `feature/ajout-fonctionnalite` ou `bugfix/correction-bug`.
- Travaillez ensuite sur cette branche.

---

## 3. **Commits fréquents et messages clairs** 📝

Faites des **commits fréquents** pour sauvegarder vos progrès. Chaque commit doit contenir des modifications cohérentes et être accompagné d'un **message de commit clair** et descriptif.

### Étapes :
- Après avoir modifié un fichier, sélectionnez-le dans GitHub Desktop.
- Ajoutez un message de commit clair comme : "Ajoute la page de connexion utilisateur".

---

## 4. **Utiliser `Fetch` régulièrement** 🚧

Même si vous travaillez sur votre propre branche, utilisez régulièrement la commande **Fetch** pour rester informé des nouvelles modifications dans le dépôt distant. Cela permet d'éviter des surprises lorsque vous fusionnez vos changements.

### Étapes :
- Cliquez sur **Fetch origin** en haut pour vérifier si des modifications ont été poussées par d'autres membres de l'équipe.

---

## 5. **Utiliser le Rebase pour un historique propre** 🔄

Si votre branche a besoin d'intégrer les dernières modifications de la branche `main` ou `master`, préférez l'option **Rebase** plutôt que **Merge**. Le rebase permet d'obtenir un historique de commits plus linéaire.

### Étapes :
- Allez dans **Branch** > **Rebase Current Branch...**.
- Choisissez la branche à partir de laquelle vous souhaitez rebaser (par exemple, `main`).

---

## 6. **Utiliser des Pull Requests pour fusionner des branches** 🔗

Pour collaborer efficacement, utilisez des **Pull Requests** pour fusionner vos branches dans la branche principale. Cela permet à d'autres membres de votre équipe de revoir votre code avant qu'il ne soit fusionné.

### Étapes :
- Une fois votre branche prête, allez sur GitHub et créez une Pull Request.
- Attendez l'approbation des autres membres de l'équipe avant de fusionner la branche.

---

## 7. **Résoudre les conflits immédiatement** ⚠️

Les conflits surviennent lorsque deux personnes modifient les mêmes lignes de code. Si vous rencontrez un conflit, résolvez-le immédiatement via GitHub Desktop ou un éditeur de code.

### Étapes :
- Lorsque GitHub Desktop signale un conflit, ouvrez les fichiers concernés dans votre éditeur de code.
- Modifiez les sections conflictuelles, sauvegardez et revenez sur GitHub Desktop pour finaliser la résolution en cliquant sur **Mark as resolved**.

---

## 8. **Nettoyer les branches obsolètes** 🗑️

Après avoir fusionné une branche via une Pull Request, supprimez-la pour garder votre dépôt propre.

### Étapes :
- Sur GitHub Desktop, allez dans **Branch** > **Delete Branch** pour supprimer la branche locale une fois qu'elle est fusionnée.
- Supprimez également la branche distante via GitHub.

---

## 9. **Vérifier l'historique des commits avant de pousser** 🔍

Avant de pousser vos commits sur le dépôt distant, utilisez GitHub Desktop pour **vérifier l'historique des commits**. Cela vous permet de vous assurer que tous les commits sont corrects.

### Étapes :
- Allez dans l'onglet **History** pour revoir tous les commits avant de les pousser.

---

## 10. **Éviter le push forcé sur une branche partagée** 🚫

Évitez d'utiliser **Force Push** sur une branche partagée, sauf si c'est absolument nécessaire. Cela peut écraser les modifications d'autres développeurs. Si vous devez utiliser `force push`, communiquez avec votre équipe avant.

### Étapes :
- Si un push forcé est nécessaire, cochez **Force Push** avant de pousser vos changements, mais soyez sûr de comprendre l'impact sur les autres membres de l'équipe.

---

## Conclusion 🎯

GitHub Desktop simplifie l'utilisation de Git, mais cela ne remplace pas de bonnes pratiques Git. En appliquant ces conseils, vous maintiendrez un workflow Git propre et collaboratif tout en évitant les conflits et autres problèmes.

---

## 📚 Ressources supplémentaires
- Documentation officielle de GitHub Desktop : [https://docs.github.com/en/desktop](https://docs.github.com/en/desktop)
- Guide des Pull Requests : [https://docs.github.com/en/pull-requests](https://docs.github.com/en/pull-requests)