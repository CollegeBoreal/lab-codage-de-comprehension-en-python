  Bienvenue dans ce laboratoire qui te guidera à écrire des programmes dans le language [Python](https://www.python.org). Les programmes se concentreront sur l'étude du language en passant par plusieurs exercices. Avant de commencer, nous allons nous assurer que l'environnement de développement est prêt. 

## :a: Installer Python 

:zero: Présence de Python

Ouvrir un terminal et vérifier la version de Python avec la commande suivante

```
% python --version
```

Si `Python` est installé, le résultat de la commande donnera une version. Cette version doit être superieure à `3.x.x`

:one: installer Python avec un `Package manager`

Si Python n'est pas installé, utiliser un gestionnaire de paquets pour l'installer.

:computer: Windows avec [choco](https://chocolatey.org/install)

```
PS > choco install python3 --pre
```

:round_pushpin: Pour tester l'installation du paquet:

```
PS > choco list python3 --local-only
Chocolatey v0.10.15
python3 3.10.0-a2
1 packages installed.
```

:apple: MacOS avec [HomeBrew](https://docs.brew.sh/Installation)

```
% brew install python@3.8
```

:round_pushpin: Forcer la version 3 pour Python

:bulb: Remplacer `~/.zshrc` par `~/.bashrc` si `bash` est utilisé. `$ echo $SHELL` pour savoir quel Shell est utilisé

```
% echo 'export PATH="/usr/local/opt/python@3.9/bin:$PATH"' >> ~/.zshrc
% echo 'alias python=python3' >> ~/.zshrc
% echo 'alias pip=pip3' >> ~/.zshrc
```

:round_pushpin: Pour tester l'installation du paquet:

```
$ brew list python
```

:warning: Ce laboratoire n'utilise pas Python **2**

## :b: Installer [Git](https://git-scm.com/downloads)

:two: Présence de Git

Ouvrir un terminal et vérifier la version de Git avec la commande suivante

```
% git --version
```

Si le résultat donne un numéro de version. C'est parfait sinon

:four: installer Git avec un `Package manager`

Si Git n'est pas installé, utiliser un gestionnaire de librairies.

:computer: Windows avec [choco](https://chocolatey.org/install)

```
PS > choco install git.install
```

:apple: MacOS avec [HomeBrew](https://docs.brew.sh/Installation)

```
% brew install git
```

## :ab: Cloner le référentiel

Maintenant que nous avons Git, nous pouvons cloner le référentiel contenant block d'assemblage du code que tu vas écrire. 

Dans un `terminal` (`git bash` :computer: Windows, `Terminal` :apple: MacOS) tapes :

- [ ] va dans le répertoire dédié au code source pour les developpeurs de programmes. (i.e Déja créé avec la commande `mkdir Developer` en cours)

```
$ cd Developer
```

- [ ] Copie le référentiel sur ton ordinateur

```
$ git clone {{ repoUrl }}
```

- [ ] change de répertoire

```
$ cd {{ repo }}
```

- [ ] Vérifie la présence de fichier et de plusieurs répertoires, tapes la commande:

```
$ ls -l
```

tu y touveras le fichier et répertoires suivants:

- `README.md`: un fichier `markdown` donnant des informations sur le laboratoire
- `01`, `02`, `...` des répertoires oû se trouvent les exercices. 

Maintenant que tout est en place, nous pouvons commencer.

Laisses un commentaire avec ton **:id:**  github pour continuer.
