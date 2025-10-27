# Cours python pour la spé math

## 1. Introduction

#### - Pré-requis

Python c'est un langage de programmation qui sert a faire des script.

(Ici on va voir python pour la spé math uniquement, plein de concept et d'idées vont etre mega vulgarisé mais c'est pour comprendre. Si tu veut apprendre plus python et voir du python simple ou avancée tu devras apprendre bcp plus de trucs que ce qui a la)

Pour installer python sur son ordi va sur ses liens : 
- https://www.python.org/downloads/ (Lien officiel de python, installe la dernière version et lors de l'installation clique bien sur ADD TO PATH (sinon rien marchera)).
- https://code.visualstudio.com/download (Editeur de code simple, parfait pour Python, installe le)

#### - Setup
Une fois que VSCode et Python sont installé tu lance VSCode et tu va dans FILE>Open Folder et tu créer un dossier et tu choisis se dossier.

Ensuite tu va dans Terminal>New Terminal. Tu devrais voir apparaitre un genre de CMD en bas de l'écran. Tape dedans `python --version` OU `py --version` (ca depend de la version de python)

Si tu vois un truc comme ca : 
```
PS C:\Users\z3rog> python --version
Python 3.12.3
```

Alors toute est bon.

#### - Premier fichier

A gauche tu aura en dessous de 'EXPLORER' le nom du dossier que tu a choisis. Quand tu va dans la partie vide tu vois une icone fichier avec un +, clique dessus et entre le nom "script.py" (.py étant l'extension par default de python).

Ensuite tu verra a gauche ton fichier ouvert, et tu pourra commencer a taper du code.

BONUS : En bas a droite ta normalement une popup qui a apparus en demander si tu voulais installer l'extension Python, tu met OUI (Engros sa sert a te dire si il ya des erreur et comment les resoudres).

# 2. Basiques de python

#### Variables

Sur Python les variables c'est comme en maths.

Par exemple si on dis que :
```
x = 8
y = 2x

donc y = 2 x 8 = 16
```

Les variable ses des endroit ou on peut stocker des nombres ou expression pour les reutiliser.

Ici dans l'exemple c'est comment on le ferais en maths. En python sa serais sa :

```py
x = 8
y = 2 * x

# ici y = 16
```

> IMPORTANT

Pour calculer en maths on fais cela : 
- Une addition se fais avec : `+`
    > Par exemple:
    >> x = 5 + 6
    >>> ici x vaut 11
- Une soustraction se fais avec : `-`
    > Par exemple:
    >> x = 5 - 6
    >>> ici x vaut -1
- Une multiplication se fais avec : `*`
    > Par exemple:
    >> x = 5 * 6
    >>> ici x vaut 30
- Une division se fais avec : `/`
    > Par exemple:
    >> x = 30 / 6
    >>> ici x vaut 5
- Une puissance se fais avec : `**`
    > Par exemple:
    >> x = 10 ** 2
    >>> ici x vaut 100

#### Print

La a present si on executais notre code yavais rien qui s'afficher c'est normal car on dis juste a python de calculer mais il affichera rien tant que on lui dis pas.

Ducoup on va utiliser la fonction print() 

(ATTENTION: les fonction en python n'ont rien a voir avec les fonction f(x) en maths)

Essaye de lancer se code :

```
x = 3
y = x * 3 - 3

print(y)
```

lance ce code en allant sur le terminal et met :

`python script.py` OU `py script.py`

et tu devrais voir : `6` s'afficher

# 2. Bibliothèque math

Après avoir vu le .zip que j'ai envoyer en entier tu sais normalement ce que c'est des boucles (for, while), variable, function etc...

On va voir la bibliothèque math.

Qui s'importe comme ca: 

```py
import math
```

Elle donne plusieurs fonctions interresante comme : 

- exp() : exponentielles
- cos() , sin() : cosinus et sinus
- PI et e (constante)
- log() et log10() : logarithm (on verra en spé math ce que c'est)
- ...

chaque fonction s'importe comme detaille dans le .zip avec 

`math.FONCTION()`

