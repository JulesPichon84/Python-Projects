
    __________  ______________  _____________   __   _______________________________________________________________
    ___  __ \ \/ /__  __/__  / / /_  __ \__  | / /   ___  __ \__  __ \_  __ \_____  /__  ____/_  ____/__  __/_  ___/
    __  /_/ /_  /__  /  __  /_/ /_  / / /_   |/ /    __  /_/ /_  /_/ /  / / /__ _  /__  __/  _  /    __  /  _____ \ 
    _  ____/_  / _  /   _  __  / / /_/ /_  /|  /     _  ____/_  _, _// /_/ // /_/ / _  /___  / /___  _  /   ____/ / 
    /_/     /_/  /_/    /_/ /_/  \____/ /_/ |_/      /_/     /_/ |_| \____/ \____/  /_____/  \____/  /_/    /____/ 

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=F70000&center=true&vCenter=true&random=false&width=435&lines=Work+smarter%2C+not+harder+!)](https://git.io/typing-svg)

![Static Badge](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&labelColor=black&color=%233776AB) ![Static Badge](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=SQLite&labelColor=black&color=%23003B57)

![Static Badge](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=Linux&labelColor=black&color=%23FCC624) ![Static Badge](https://img.shields.io/badge/Windows-0078D4?style=for-the-badge&logo=Windows&labelColor=black&color=%230078D4) ![Static Badge](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&labelColor=black&color=%232496ED)

</div>

# Bienvenue dans l'antre consacré au langage de programmation Python.

## Voici l'arborescence du dossier:
    TP2
     |
     |___README.md
     |___main.py
     |___interface.py
     |___Images/
     |___Sounds/
     |___requirements.txt
     |
     |___exo/
          |
          |___pycache
          |___exo1.py
          |___exo2_3.py
          |___exo4.py
          |___exo5.py
     
<br>

## Lors de votre arrivée dans la racine du projet, vous trouverez plusieurs fichiers et dossiers:
  1- Le fichier *main.py* représente le point d'entrée du programme, c'est par lui que tout commence.<br>
  2- Le fichier *interface.py* définit l'interface utilisateur du programme à l'aide du module Tkinter et permet d'appeler les différents exercices du TP.<br>
  3- Le fichier *requirements.txt* contient la liste des modules nécessaires pour le bon fonctionnement du programme.<br>
  4- Les dossiers *Images* et *Sound* contiennent toutes les images et les sons pour l'interface utilisateur.<br>
  5- Enfin, le dossier *exo* contient tous les exercices du TP.

<br>

Si vous souhaitez avoir un exécutable sous **Windows**, il vous suffit d'exécuter le code suivant:
  ```shell
  pyinstaller --onefile main.py
  ```

<br>

Si vous souhaitez avoir un exécutable sous **Linux**, il vous suffit d'exécuter le code suivant:
  ```shell
  pip install cx_Freeze
  ```

<br>

Créer ensuite un fichier setup.py et placez les lignes de code suivantes:
  ```python
   from cx_Freeze import setup, Executable

   setup(
        name="",
        version="",
        description="",
        executables=[Executable("main.py")])
  ```

<br>

Puis exécuter la commande suivante:
  ```shell
   python setup.py build
  ```

Volume horaire total:

| Tâches  | Heures |
| ------------- | ------------- |
| Développement des Scripts Python  | X |
| Développement du GUI  | X |
| Liaison du GUI aux Scripts | X |
| Rédaction documentation| X |
| Total | X |

Roadmap des tâches:

- [ ] Les scripts pour les 5 exercices.
- [ ] Développement UI 
- [ ] Création des graphiques avec tracés de courbes.
- [ ] Création d'une documentation pour l'utilisateur.
- [ ] Réaliser les tests unitaires.
- [ ] Centrer le cadre contenant le titre et les boutons au centre de la fenêtre tkinter.
- [ ] Création d'un Dokerfile en cours mais problème au moment d'exécuté le conteneur. Non prise en charge de tkinter de façon native.
- [ ] Bonus: Ajouter une étape de sécurité avant de lancer le programme.

> [!TIP]
> Si vous souhaitez effectuer vos propres personnalisations, voici des liens utiles menant vers la documentation des modules que j'ai utilisé pour les projets:
>  - Visit https://seaborn.pydata.org/index.html
>  - Visit https://matplotlib.org/stable/tutorials/pyplot.html
>  - https://numpy.org/doc/stable/
>  - https://scapy.readthedocs.io/en/latest/
>  - https://pandas.pydata.org/docs/index.html
>  - https://docs.scipy.org/doc/scipy/
>  - https://requests.readthedocs.io/en/latest/
>  - https://scrapy.org/


> [!WARNING]
> Si vous rencontrez des problèmes avec les programmes, vous pouvez m'envoyer un message !

## Amusez-vous bien avec ces exercices, et surtout n'oubliez pas d'activer le son de votre ordinateur !
