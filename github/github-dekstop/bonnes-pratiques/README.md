# 🎯 Bonnes pratiques Git avec GitHub Desktop 🎯

GitHub Desktop est un excellent outil pour simplifier l'utilisation de Git avec une interface graphique conviviale. Cependant, même avec une interface simple, il est important de suivre certaines bonnes pratiques pour garantir un workflow Git propre et éviter les conflits.

---

## 🔄 1. Toujours synchroniser avant de commencer à travailler

Avant de commencer à travailler sur un projet, **synchronisez** toujours votre dépôt local avec le dépôt distant. Cela vous assure d'avoir les dernières modifications avant de faire vos changements.

### 🚀 Étapes :
- Cliquez sur **Fetch origin** pour récupérer les dernières modifications.
- Puis, cliquez sur **Pull origin** pour les intégrer à votre dépôt local.

---

## 🌿 2. Créer une branche pour chaque fonctionnalité ou correction

Ne travaillez pas directement sur la branche `main` ou `master`. Créez une **nouvelle branche** pour chaque fonctionnalité ou correction de bug.

### 🔧 Étapes :
- Allez dans **Branch** > **New Branch...**.
- Donnez un nom explicite à la branche, comme `feature/ajout-fonctionnalite` ou `bugfix/correction-bug`.

---

## ✨ 3. Faire des commits fréquents et utiliser des messages clairs

**Commitez fréquemment** pour sauvegarder vos progrès. Chaque commit doit être accompagné d'un **message descriptif** qui explique clairement ce qui a été fait.

### 💬 Exemple :
- Après avoir modifié un fichier, sélectionnez-le.
- Ajoutez un message de commit clair : `"Ajout de la fonctionnalité de connexion utilisateur"`.

---

## 🚧 4. Utiliser `Fetch` régulièrement pour rester informé

Même si vous travaillez sur une branche distincte, **Fetch** régulièrement pour voir s'il y a des changements sur le dépôt distant.

### 🔄 Étapes :
- Cliquez sur **Fetch origin** pour vérifier si des modifications ont été poussées par d'autres membres de l'équipe.

---

## 🔀 5. Utiliser le Rebase pour un historique propre

Pour maintenir un historique linéaire, préférez le **Rebase** plutôt que le Merge lorsque vous intégrez les changements de `main` dans votre branche.

### 📘 Étapes :
- Allez dans **Branch** > **Rebase Current Branch...**.
- Choisissez la branche à partir de laquelle vous voulez rebaser (par exemple `main`).

---

## 📢 6. Utiliser les Pull Requests pour collaborer efficacement

Utilisez des **Pull Requests** pour fusionner vos branches dans la branche principale. Cela permet à d'autres développeurs de réviser votre code avant qu'il ne soit fusionné.

### ✅ Étapes :
- Une fois prêt, allez sur GitHub et créez une Pull Request pour demander une revue de code.

---

## ⚡ 7. Résoudre les conflits immédiatement

Si vous rencontrez un conflit, **résolvez-le immédiatement** via GitHub Desktop ou un éditeur de code.

### ⚠️ Étapes :
- Quand GitHub Desktop signale un conflit, ouvrez les fichiers concernés, corrigez les conflits, puis revenez à GitHub Desktop pour marquer les conflits comme résolus.

---

## 🧹 8. Supprimer les branches obsolètes

Après avoir fusionné une branche, supprimez-la pour garder votre dépôt propre.

### 🗑️ Étapes :
- Sur GitHub Desktop, allez dans **Branch** > **Delete Branch** pour supprimer la branche locale.
- Sur GitHub, supprimez aussi la branche distante.

---

## 🔍 9. Vérifier l'historique avant de pousser

Avant de pousser vos commits, passez en revue l'historique des commits pour vérifier que tout est correct.

### 📜 Étapes :
- Allez dans l'onglet **History** pour revoir les commits récents.

---

## 🚫 10. Éviter le `Force Push` sur une branche partagée

N'utilisez **Force Push** que si c'est absolument nécessaire, et après en avoir parlé à l'équipe. Cela peut entraîner des pertes de données pour les autres contributeurs.

### ⚠️ Étapes :
- Si vous devez utiliser Force Push, cochez l'option avec prudence.

---

## 🎉 Conclusion

En suivant ces bonnes pratiques, vous aurez un workflow Git plus fluide, collaboratif et exempt de conflits. GitHub Desktop simplifie la gestion de Git, mais ces principes sont essentiels pour une bonne gestion de version en équipe.

---

## 📚 Ressources utiles :
- [Documentation officielle GitHub Desktop](https://docs.github.com/en/desktop)
- [Guide des Pull Requests](https://docs.github.com/en/pull-requests)
