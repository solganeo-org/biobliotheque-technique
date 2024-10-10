
# Commandes Git essentielles et avancées 🛠️

Cette section répertorie les commandes **Git** les plus utilisées, accompagnées d'explications simples et d'exemples. Ces commandes sont utilisables via **Git Bash** sous Windows, Linux, et MacOS.

---

## 📂 Commandes de base

### 1. `git init` 🏁
**Description** : Initialise un nouveau dépôt Git dans le répertoire courant.

**Exemple** :
```bash
git init
```
Cela crée un dossier `.git` qui contient toutes les informations du dépôt Git. Utilisez cette commande pour démarrer un nouveau projet Git.

---

### 2. `git clone` 📥
**Description** : Clone un dépôt distant (sur GitHub par exemple) sur votre machine locale.

**Exemple** :
```bash
git clone https://github.com/utilisateur/nom-du-repo.git
```
Cela télécharge une copie complète du dépôt distant sur votre ordinateur.

---

### 3. `git status` 📊
**Description** : Affiche l'état actuel du dépôt (modifications non commitées, fichiers suivis, etc.).

**Exemple** :
```bash
git status
```
Cela vous indique les fichiers modifiés, ajoutés ou supprimés qui ne sont pas encore commitées.

---

### 4. `git add` ➕
**Description** : Ajoute des fichiers modifiés au staging (prépare les fichiers pour le commit).

**Exemple** :
```bash
git add nom-du-fichier.txt
```
Ou pour ajouter tous les fichiers modifiés :
```bash
git add .
```
Cela place les fichiers dans la zone de staging, prêts à être commitées.

---

### 5. `git commit` 💾
**Description** : Enregistre les modifications dans l'historique du projet avec un message de description.

**Exemple** :
```bash
git commit -m "Message de commit"
```
Cela enregistre un snapshot de vos modifications avec un message explicatif. Utilisez un message clair pour décrire les changements effectués.

---

## 🚀 Commandes pour collaborer avec un dépôt distant

### 6. `git pull` 🔄
**Description** : Récupère les modifications depuis le dépôt distant et les intègre à votre dépôt local.

**Exemple** :
```bash
git pull origin main
```
Cela fusionne les changements du dépôt distant avec votre branche locale. À utiliser régulièrement pour rester à jour avec les modifications du dépôt distant.

---

### 7. `git push` 🚀
**Description** : Envoie vos commits locaux vers le dépôt distant (GitHub par exemple).

**Exemple** :
```bash
git push origin main
```
Cela envoie vos changements sur la branche `main` du dépôt distant. Vous devez être à jour avec le dépôt distant avant de pousser.

---

## 🔧 Commandes pour la gestion des branches

### 8. `git branch` 🌿
**Description** : Liste toutes les branches locales dans le dépôt.

**Exemple** :
```bash
git branch
```
Cela affiche toutes les branches dans votre dépôt, avec un `*` indiquant la branche active.

---

### 9. `git checkout` et `git checkout -b` 🔄
**Description** :
- `git checkout nom-de-la-branche` : Change de branche.
- `git checkout -b nom-de-la-branche` : Crée une nouvelle branche et se place dessus.

**Exemple** :
```bash
git checkout -b nouvelle-branche
```
Cela crée et passe sur une nouvelle branche nommée `nouvelle-branche`. Très utile pour travailler sur de nouvelles fonctionnalités sans affecter la branche principale.

---

### 10. `git merge` 🔗
**Description** : Fusionne une branche avec la branche courante.

**Exemple** :
```bash
git merge nom-de-la-branche
```
Cela intègre les modifications d'une autre branche dans la branche active. Utilisez cette commande après avoir terminé le travail sur une branche secondaire.

---

## 🧹 Commandes pour gérer l'historique

### 11. `git log` 📜
**Description** : Affiche l'historique des commits dans la branche actuelle.

**Exemple** :
```bash
git log
```
Cela liste tous les commits effectués dans la branche courante, avec l'auteur, la date et le message du commit.

---

### 12. `git reset` ❌
**Description** : Annule des commits ou des modifications non souhaitées.

**Exemple** :
```bash
git reset --hard HEAD~1
```
Cela annule le dernier commit et remet les fichiers à l'état précédent. Utilisez cette commande avec précaution car elle peut détruire des modifications non poussées.

---

## 🚨 Commandes supplémentaires utiles

### 13. `git stash` 💼
**Description** : Met temporairement de côté les modifications en cours de travail sans les commiter.

**Exemple** :
```bash
git stash
```
Cela sauvegarde vos changements actuels sans les commiter, afin que vous puissiez revenir à une version propre du dépôt.

---

### 14. `git rebase` 🛠️
**Description** : Rebase une branche sur une autre pour réécrire l'historique des commits.

**Exemple** :
```bash
git rebase main
```
Cela permet de replacer les commits de votre branche courante sur une autre branche (`main` dans cet exemple) pour obtenir un historique linéaire. À utiliser avec prudence.

---

## 📚 Ressources supplémentaires
- Documentation officielle de Git : [https://git-scm.com/doc](https://git-scm.com/doc)
- Tutoriels interactifs sur Git : [https://learngitbranching.js.org/](https://learngitbranching.js.org/)