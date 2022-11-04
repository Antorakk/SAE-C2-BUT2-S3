# **Empilement d’images astronomiques 🪐**

> Auteur : ELUECQUE Anthony & DOURNEL Frédéric

# **Sommaire 📃**

- 1 But du projet
- 2 Prérequis
    - 2.1 Langage de programmation
        - 2.1.1 Quel langage ?
        - 2.1.2 Avantages
        - 2.1.3 Inconvénients
    - 2.2 Librairies
        - 2.2.1 Astropy
        - 2.2.2 PyQt
        - 2.2.3 Matplotlib
        - 2.2.4 Numpy
        - 2.2.5 Scikit-image
        - 2.2.6 Pyinstaller
- 3 Fonctionnalités
    - 3.1 Fonctionnalités attendus :
        - 3.1 Stacking
            - 3.1.1 Stacking par moyenne
            - 3.1.2 Stacking par médiane
    - 3.2 Fonctionnalités supplémentaires
        - 3.2.1 Détection des étoiles
        - 3.2.2 Détection des outliers
        - 3.2.3 Modification de l'intensité
        - 3.2.4 Détection des maximas locaux
    - 3.3 Graphique
- 4 Comment l'utiliser ?
    - 4.1 Lancer le programme
        - 4.1.1 Avec le code
        - 4.1.2 Avec l'exécutable
    - 4.2 Utilisation de l'interface
        - 4.2.1 Ouvrir une image
        - 4.2.2 Stacking d'une image
        - 4.2.3 Filtre sur une image
            - 4.2.3.1 Detection des outliers
            - 4.2.3.2 Modification de l'intensité
        - 4.2.4 Enregistrer l'image




## **1 but du projet 📌**

Le but du projet est de faire un empilement d'image d'une même scène avec plusieurs prises
de vue afin qu'une image obtienne une meilleure qualité. Ce procédé est surtout utiliser 
en astrophotographie pour avoir une meilleure qualité des photos qui sont prisent à des années
lumières de distance.

Pour faire cela nous devons manipuler des images sous extensions _.FITS_ et ensuite les stacker pour améliorer
la qualité de l'image.

## **2 Les prérequis 🛠️**

### 2.1 Langage de programmation ⚙️
 
> #### 2.1.1 Quel langage ? 🔠

Pour ce projet, nous avons utilisé **_Python_**. 

<sub>Python : https://www.python.org/</sub>

> #### 2.1.2 Avantages ✅

Les avantages qu'on **_Python_** pour ce projet sont nombreux. 
 - Dispose de nombreuses librairies pour le traitement d'image.
 - Facilité de développement du fait que **_Python_** est haut niveau.
 - Langage très connu des développeurs.
 
> #### 2.1.3 Inconvénients ❌

Malheureusement, **_Python_** a également de nombreux défauts.
 - Le programme est lent pour les gros calculs
 - 

### 2.2 Librairies 📚

> #### 2.2.1 Astropy 🌌

**_Astropy_** est au coeur de notre projet, cette librairies nous permet d'ouvrir et d'utiliser les images avec l'extension "_.fits_".

```
pip install Astropy
```

<sub>Astrpy : https://www.astropy.org/</sub>

> #### 2.2.2 PyQt 🪟

**_PyQt_** est un module libre qui permet de lier le langage Python avec la bibliothèque Qt.
Celle-ci permet de créer des intefaces en ayant différents outils pour cela.

```
pip install PyQt6
```

<sub>PyQt : https://doc.qt.io/qtforpython/ </sub>

> #### 2.2.3 Matplotlib 📊

Nous avons utiliser **_Matplotlib_** pour afficher les images sur l'interface **_PyQt_** et créer les graphiques en lien avec l'image.
Nous utilisons plus particulièrement **_Matplotlib.Pyplot_**.

```
pip install Matplotlib
```

<sub>Matplotlib : https://matplotlib.org/</sub>

> #### 2.2.4 Numpy

La bibliotèque **_Numpy_** nous à permit de travailler avec les données d'une image fits. En effet, ces images sont composées de _"numpy.array"_  pour stocker la couleur des pixels. 

```
pip install Numpy
```

<sub>Numpy : https://numpy.org/</sub>

> #### 2.2.5 Scikit-image

**_Scikit-image_** nous a permit de réaliser les filtres sur les images. 

```
pip install Scikit-image
```

<sub>Scikit-image : https://scikit-image.org//</sub>

> #### 2.2.6 Pyinstaller

Grâce à **_Pyinstaller_**, nous avons pu créer un executable (_.exe_) pour une ouverture sumplifier de l'interface.

```
pip install Pyinstaller
```

<sub>Pyinstaller : https://pyinstaller.org/</sub>


## **3 Fonctionnalités ➕**

### **3.1 Fonctionnalités attendues**

> #### 3.1.1 Stacking par moyenne

Cette méthode de stacking permet de rendre l'image plus net. Pour faire cela on prend les pixels des toutes les images dans chaque coordonnées de l'image pour ensuite faire la moyenne de ces données et ensuite d'attribuer la moyenne comme couleur de ce pixel.

> #### 3.1.2 Stacking par médiane

Le stacking par médiane permet de rendre l'image encore plus net qu'avec le stacking par médiane. Pour faire cela on prend les pixels des toutes les images dans chaque coordonnées de l'image pour ensuite prendre la médiane de ces données et ensuite d'attribuer cette valeur comme couleur de ce pixel.

> #### 3.1.3 Détection des outliers

### **3.2 Fonctionnalités supplémentaires**

> #### 3.2.1 Detection des étoiles ⭐

Antho

> #### 3.2.1 Detection des outliers



> #### 3.2.2 Modification de l'intensité

Antho

> #### 3.3 Detection des maximas locaux



### **3.3 Graphique**

Antho

## **4 Comment l'utiliser ❔**

### 4.1 Lancer le programme ▶️

> #### 4.1.1 Avec le code 

Pour utiliser le programme à partir du code, il faut run le fichier **mainWindow.py** grâce à un éditeur de code comme _VS code_.

<sub>VS code : https://code.visualstudio.com</sub>

> #### 4.1.2 Avec l'exécutable

Double clicker sur le fichier **nomDuFichier.exe** et l'interface s'ouvrira.

### 4.2 Utilisation de l'interface 

> #### 4.2.1 Ouvrir une image

Une fois dans l'interface, il vous suffit de cliquer sur le bouton _"ouvrir un fichier"_ et de choisir votre photo au format _".fits"_. Ou bien ouvrir un dossier si vous avez un dossier avec plusieurs photo à empiler.

<img src="./img/Ouvrirfichier.png">

> #### 4.2.2 Stacking d'une image

Pour faire du stacking sur une image, il vous suffit de cliquer sur le menu déroulant _"Méthode Stacking"_ et choississez ensuite votre méthode de stacking entre le _stacking moyenne_ ou le _stacking médiane_.

<img src = "./img/stacking.png">

> #### 4.2.3 Filtrer une image

Pour choisir un filtre sur une image stackée, il vous faut cliquer sur le nouveau menu déroulant _"Choisir un filtre"_ et chossissez par la suite le filtre que vous voulez.

<img src = "./img/filtre.png">

> ##### 4.2.3.1 Detection des outliers

> ##### 4.2.3.2 Modification de l'intensité

> #### 4.2.4 Enregistrer l'image

Pour enregister votre image en format _".png"_, il vous suffit de cliquer sur le bouton "_Enregistrer en PNG"_ ainsi que de choisir l'emplaceent du futur fichier.

<img src = "./img/enregistrer.png">










 
