# Exercice :three:

- [ ] Change de répertoire

```
$ cd 03
```

- [ ] Ouvre le fichier `programme.py` avec `nano`


```
$ nano programme.py
```

- [ ] Modifier le programme permettant d'imprimer une liste de nombre pairs

remplacer les `???` du code ci-dessous par l'énoncé ci-dessus

```python
# -*- coding: utf-8 -*-
"""

@author: CollegeBoreal
"""

def exo_03(liste):
  # Selectionner une liste de nombre pairs uniquement
  pairs = ??? 
  return sorted(pairs)

def main():
  print( exo_03( [ 3, 5, 7, 9, 98, 13, 24, 56, 17, 9, 8 ] ) )

if __name__== "__main__":
  main()
```

- [ ] Fais tourner ton programme dans ton terminal

Pour éxécuter le programme Python tape `python programme.py` dans le terminal. Le programme Python doit se trouver dans le même répertoire ou l'on se trouve.

```
$ python programme.py
```

Après l'éxécution, sur ton terminal s'affichera la liste triée de nombres pairs: `[8, 24, 56, 98]`. Nous ferons encore mieux dans quelques instants mais pour l'instant, il faut soumettre le code vers GitHub. 


- [ ] Soumettre les modifications

Pour chaque changement de fichiers dans ton référentiel, il faut  `ajouter` et `signer` le fichier qui te permet de formuler un message detailant ce que tu as changé. Ensuite tu peux `soumettre` une version mise à jour, en même temps que tes commentaires, vers GitHub. 

:round_pushpin: Faisons ces quatres étapes:

1. Ajouter dans Git: `git add programme.py`
2. Signer dans Git: `git commit -m "Ajout de la fonction exo_03() nombres pairs"`
3. Récuperer la correction: `git pull`      
         :bulb: Pour valider la récupération dans `nano` utiliser la combinaison - `^O WriteOut` + `Enter` + `^X Exit`
3. Soumettre à Git: `git push`
4. Revenir au répertoire principal: `cd ..`
