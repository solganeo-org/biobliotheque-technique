
# Installation de Git sur Windows, Linux et MacOS 🖥️

Git est un outil essentiel pour la gestion de versions dans les projets de développement. Suivez ce guide pour installer Git sur votre machine, quel que soit le système d'exploitation que vous utilisez.

---

## 🪟 Installation de Git sur **Windows**

### 1. Télécharger Git 🛠️
- Rendez-vous sur la page officielle de Git : [Git for Windows](https://git-scm.com/download/win).
- Téléchargez l'installeur pour Windows.

### 2. Exécuter l'installateur 🖱️
- Une fois téléchargé, lancez l’installateur.
- Laissez les options par défaut, sauf si vous avez des besoins spécifiques.
- Lorsque vous atteignez la fenêtre **Adjusting your PATH environment**, sélectionnez **Git from the command line and also from 3rd-party software**.
- Cliquez sur **Next** pour terminer l'installation.

### 3. Vérification de l'installation 🔍
- Ouvrez **Git Bash** (installé automatiquement avec Git).
- Tapez la commande suivante pour vérifier la version de Git :

  ```bash
  git --version
  ```

Si la commande affiche une version (par exemple, `git version 2.33.0`), Git est bien installé !

---

## 🐧 Installation de Git sur **Linux**

### 1. Ouvrir un terminal 💻
L'installation de Git dépend de votre distribution Linux. Voici les commandes pour les distributions les plus courantes.

### 2. Installer Git avec le gestionnaire de paquets 📦

#### Sur **Ubuntu / Debian** :
```bash
sudo apt update
sudo apt install git
```

#### Sur **Fedora** :
```bash
sudo dnf install git
```

#### Sur **Arch Linux** :
```bash
sudo pacman -S git
```

### 3. Vérification de l'installation 🔍
- Tapez la commande suivante pour vérifier la version de Git :

  ```bash
  git --version
  ```

Si une version s’affiche (par exemple, `git version 2.33.0`), vous avez installé Git avec succès !

---

## 🍏 Installation de Git sur **MacOS**

### 1. Utiliser Homebrew (méthode recommandée) 🍺
- Si vous n'avez pas encore **Homebrew** installé, installez-le d'abord en suivant les instructions sur [brew.sh](https://brew.sh/).

- Une fois Homebrew installé, ouvrez le **Terminal** et exécutez la commande suivante pour installer Git :

  ```bash
  brew install git
  ```

### 2. Alternative : Utiliser Xcode Command Line Tools 🛠️
- Si vous préférez, vous pouvez aussi installer Git via les outils en ligne de commande Xcode. Ouvrez le terminal et tapez :

  ```bash
  xcode-select --install
  ```

- Suivez les instructions à l'écran pour installer Git via les outils Xcode.

### 3. Vérification de l'installation 🔍
- Ouvrez le terminal et tapez la commande suivante pour vérifier la version de Git :

  ```bash
  git --version
  ```

Si une version s’affiche (par exemple, `git version 2.33.0`), Git est bien installé !

---

## 🎉 Git est installé ! Et maintenant ?

Maintenant que Git est installé, vous pouvez commencer à l'utiliser pour gérer vos projets. Voici quelques commandes de base pour commencer :

### Configurer Git avec votre nom et email (important !) 📝

```bash
git config --global user.name "Votre nom"
git config --global user.email "votre.email@example.com"
```

### Vérifier la configuration actuelle de Git 🔍
```bash
git config --list
```

---

## 🚀 Prochaines étapes
Maintenant que Git est prêt, passez à l'étape suivante : **Créer un dépôt et commencer à utiliser Git !**

Vous pouvez explorer plus d'options avec Git et vous perfectionner, mais pour l’instant, vous êtes prêt à démarrer vos premiers projets en gestion de version ! 😄

---

## 📚 Ressources supplémentaires
- Documentation officielle de Git : [https://git-scm.com/doc](https://git-scm.com/doc)
- Apprendre Git avec des tutoriels interactifs : [https://learngitbranching.js.org/](https://learngitbranching.js.org/)