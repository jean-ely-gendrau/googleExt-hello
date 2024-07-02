# 🌟 Bienvenue dans Votre Première Extension Google Chrome

Ce projet vous guidera à travers le processus de création, mise en service et test de votre première extension Google Chrome. Ce tutoriel est conçu pour les débutants et vous introduira aux concepts clés du développement d'extensions Chrome.

[à tout moment consultez le wiki !](https://github.com/jean-ely-gendrau/googleExt-hello/wiki)

## 📚 Description

Vous apprendrez à :
- Initialiser la structure de dossiers et fichiers pour votre extension.
- Configurer le fichier `manifest.json`.
- Ajouter des icônes à votre extension.
- Charger et tester votre extension dans Chrome.

Pour des icônes gratuites et attrayantes, consultez [Icons8](https://icones8.fr/).

## 📂 Structure du Projet
```terminal
my-extension/
├── images/
│ ├── icon16.png
│ ├── icon48.png
│ └── icon128.png
├── popup/
│ ├── popup.html
│ ├── popup.js
│ └── popup.css
└── manifest.json
```

## 🚀 Guide d'Initialisation du Repository

### 1. Créer le Repository GitHub

>[!WARNING]
>Remplacer les valeur sivante:
>USERNAME par le votre `USERNAME` GitHub
>my-extension par le nom de votre repositorie

Utilisez l'outil [CLI de GitHub](https://cli.github.com/) `gh` pour créer votre repository :

>[!TIP]
>Pour utiliser l'outil CLI de GitHub il faut être authentifié
>[S'authentifié avec la CLI gh auth login](https://cli.github.com/manual/gh_auth_login)
```sh
gh repo create my-extension --public --description "Votre première extension Google Chrome"
```

2. Cloner le Repository
Clonez le repository que vous venez de créer :
```sh
git clone https://github.com/USERNAME/my-extension.git
cd my-extension
```

3. Créer les Issues
Créez les issues nécessaires pour suivre les étapes de développement :

- Initialisation de la Structure de l'Extension :
```terminal
gh issue create --title "initialiser/Réaliser La première extension" --body "https://github.com/USERNAME/my-extension/issues/2"
```

- Mise en Service et Test de l'Extension :
```terminal
gh issue create --title "Mise en Service et Test de l'Extension" --body "https://github.com/USERNAME/my-extension/issues/2"
```
[à tout moment consultez le wiki !](https://github.com/jean-ely-gendrau/googleExt-hello/wiki)

### 🔗 Liens vers les Issues
- [Initialisation de la Structure de l'Extension](https://github.com/jean-ely-gendrau/googleExt-hello/issues/2)
- [Mise en Service et Test de l'Extension](https://github.com/jean-ely-gendrau/googleExt-hello/issues/1)

Félicitations ! Vous avez créé vos deux premières issues de projet. Cela facilitera le travail de développement pour vous ou votre équipe, si vous travaillez en groupe. Maintenant, il est important de créer une milestone pour organiser et structurer les étapes cruciales du développement.

_Une milestone vous permet de regrouper plusieurs issues liées à une même phase du projet, rendant ainsi le suivi et la gestion plus efficaces. Pour créer une milestone sur GitHub_ :

- Accédez à l'onglet "Issues" de votre dépôt.
- Cliquez sur "Milestones" et ensuite sur "New milestone".
- Donnez un titre clair et descriptif à votre milestone.
- Ajoutez une description détaillée pour expliquer les objectifs de cette étape.
- Définissez une date d'échéance si nécessaire.

### Ensuite, associez vos issues à la milestone créée. Pour cela :

- Ouvrez chaque issue que vous souhaitez inclure.
- Dans la section "Milestone" à droite, sélectionnez la milestone appropriée.
- Vous pouvez également utiliser le symbole # dans les commentaires ou descriptions pour lier directement d'autres issues ou pull requests.

**_En suivant ces étapes, vous pourrez mieux gérer et suivre l'avancement de votre projet_**.

[à tout moment consultez le wiki !](https://github.com/jean-ely-gendrau/googleExt-hello/wiki)

### 🏆 Milestone
Pour une vue d'ensemble des étapes du projet, consultez la Milestone : Création et Déploiement de la Première Extension Google Chrome.

### 📜 License
Ce projet est sous licence MIT. Voir le fichier LICENSE pour plus de détails.
