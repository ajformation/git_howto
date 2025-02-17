# Prérequis

## Compte et repo

Créer un compte sur (au choix) :

- <https://github.com/> : Le leader mondial (87% pdm est.)
- <https://gitlab.com/> : Le challenger (15% pdm est.)
- <https://bitbucket.org/> : La référence Atlassian
- <https://www.codebasehq.com/> : Une alternative
- <https://launchpad.net/> : La base de code des produits ubuntu
- <https://azure.microsoft.com/en-us/products/devops/> : La référence pour le code hébergé pour azure
- <https://framagit.org/> : Une alternative associative.

Sur ce howto on va se baser sur Gitlab, toutes ces alternatives sont compatibles avec ce qu'on va voir.

## Créer un premier projet

Sur gitlab, une fois connecté :

- On clic sur **"+"**

![alt text](images/image.png)

- Puis sur **"New project/repository"**

![alt text](<images/Capture d’écran du 2025-02-01 16-38-17.png>)

- Puis enfin sur **"Create blank project"**

![alt text](images/image-1.png)

- On ajoute un nom à ce projet
- On choisi "l'espace" (ici notre utilisateur)

> *On verra peut être plus tard l'intérêt de créer des groupes*

![alt text](images/image-2.png)

- On fait les derniers réglages

![alt text](images/image-3.png)

- On se retrouve sur la page du projet

![alt text](images/image-4.png)

## Initialisation de votre compte

Comme indiqué dans votre projet :

![alt text](images/image-7.png)

Créez une clé ssh (ou plus simple utilisez celle que vous avez déjà)

Et dans votre compte gitlab allez l'ajouter :

![alt text](images/image-8.png)

![alt text](images/image-9.png)

![alt text](images/image-10.png)

![alt text](images/image-11.png)

On vient de finir la partie préparation.

## Installer GIT

### Linux

```shell
. /etc/os-release
case $ID_LIKE in "debian") sudo apt install git ;; *"rehl"*|*"fedora"*) sudo dnf install git ;;  "*") echo 'get over it!' ;; esac
```

### Windows

- GitBash : <https://git-scm.com/downloads/win>
- Windows terminal : <https://apps.microsoft.com/detail/9n0dx20hk701?hl=fr-FR&gl=FR>

Mon conseil : Installer **vscode** et **gitbash** et de lancer un terminal dans vscode.

![alt text](images/image-5.png)

Puis de selectionner un terminal gitbash

![alt text](images/image-6.png)

[Utiliser Git](./2_utiliser_git.md)
