---

# FILENAME : please use your OpenClassrooms's name, available in your url.
# Example: https://openclassrooms.com/membres/celinemartinet
# must be the name of your file. If file name is celinemartinet.md, title is celinemartinet.
# lowercase, no blank space, Capital case or special character.
title: loictessier

# First name or full name
name: Loïc
date: 2017-09-18 16:00

# One line.
# If you need more space, go to the next line and add 4 spaces on the left, as in 'description'.
objective: Apprendre le python.
short_description: J'aime l'informatique, les jeux et les univers fantastiques.

# don't touch that
template: students
description:
    Diplomé d'une école d'ingénieur en informatique avec deux ans d'expérience en tant
    que consultant intégrateur je souhaite apprendre de nouveaux langages et outils.

# image must be located in content/images/students
# name should be the same as this file. Eg: celinemartinet.png
image: loictessier.png

# Change this to True when you do you pull request.
public: True

# You need to keep the exact same structure for each new project.
projects:
  - title: Présentez-vous !
    description: Une présentation de moi-même et un lien vers mon LinkedIn.
    # Create a new repository for your images. Name it the same as your nickname and profile picture.
    # Image must be here: content/students/yourrepo/project1.png
    image: loictessier/projet1.png
    link: https://www.linkedin.com/in/loictessier/
    # 'true' makes it fully available.
    # 'false' will add a black layer on the picture. IT WILL BE PUBLIC!
    finished: true
  - title: Intégrez la communauté !
    description: Modifier un projet Open Source pour comprendre le fonctionnement de Git, de Github et des pull requests. 
    image: loictessier/projet2.png
    link: https://openclassrooms-student-center.github.io/alumnis/students/loictessier.html
    finished: true
  - title: Aidez MacGyver à sortir !
    description: Création d’un jeu développé en Python et utilisant PyGame.
    image: loictessier/projet3.png
    link: https://github.com/loictessier
    finished: false
---