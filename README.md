# WasteManager


Waste Manager

Contexte
Afin d'aider les communes à améliorer leur gestion des déchets, vous devez programmer un logiciel qui aura pour fonction d'assigner les différents déchets générés par les acteur.ices de la commune aux services de traitement des déchets disponibles.
Plusieurs types de déchets existent pour le moment, mais il est probable que d'autres se rajoutent par la suite (la conception devra le prendre en compte) :

déchets gris, le déchet de base
plastiques, qui seront de différents types
papiers / cartons
déchets organiques
verres
métaux

Plusieurs services de traitements des déchets seront disponibles (de même, d'autres peuvent exister par la suite) :

incinérateur, qui accepte tout type de déchets
centre de recyclage, peuvent traiter cartons et/ou plastiques, potentiellement selon leur type
composteurs de quartier, peuvent traiter les déchets compostables

en option, centre de tri des déchets recyclables, se charge de trier les déchets pour les envoyer aux centres de traitements adéquat (optionnel mais intéressant, rajoute un intermédiaire)

Chacun de ces services de traitement a une capacité de traitement définie en tonnes et rejette du CO2 relatif au nombre de déchets traités.

Mise en oeuvre
En utilisant le langage objet que vous souhaitez (défaut PHP), vous allez devoir créer un programme qui acceptera en entrée un fichier json contenant les déchets ainsi que les services de traitement des déchets disponibles, et afficher le résultat de la répartition des déchets ainsi que le CO2 rejetté (par chaque service de traitement et au global).
L'idéal est de favoriser les traitement adaptés et de ne se replier sur les autres méthodes de traitement que lorsque les capacités maximales d'un services sont atteintes.
Vous allez devoir utiliser les différents principes de la POO (SOLID) et ses outils (classes, héritage, interfaces, abstraction, etc.) pour réaliser ce programme.

Consignes de rendu

L'ensemble des éléments du rendu sera disponible sur le dépôt GitHub ou GitLab que vous enverrez dans Simplonline :

un document présentant l'approche initiale sur la démarche que vous souhaitez mettre en place pour réaliser le projet (méthodologie, tâches, planning, organisation…) (pdf, md, txt)
un document détaillant votre avancement (tâche, temps passé, difficultés rencontrés, solutions mise en place…) (pdf, md, txt)
un diagramme de classes (pdf, jpg, png)
un document expliquant comment installer et utiliser votre projet (pdf, md, txt)
le code source


Le premier commit ne devra contenir que le fichier présentant l'approche initiale.
Des commits réguliers (plusieurs par jour) seront réalisés avec des commentaires pertinents.
Le code source ainsi que les messages des commits seront en anglais.
