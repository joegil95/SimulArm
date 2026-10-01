# SimulArm
Ce logiciel est un simulateur de microcontrôleur de type ARM STM32 destiné à un usage pédagogique. 
C’est un simulateur de haut niveau, qui travaille au niveau du programme en langage C, 
en s’appuyant sur des librairies de simulation dont l’équivalent existe dans la réalité 
(Voir https://github.com/joegil95/Libraries-for-Olimex-E407-STM32F407-), 
de sorte qu’il est très facile de transposer un programme réalisé dans le simulateur en un programme 
fonctionnant sur le véritable microcontrôleur.

Ce logiciel N’EST PAS un simulateur de bas niveau, et n’est donc pas fait pour simuler l’exécution
d’un code compilé. De tels simulateurs existent à ce jour mais sont très incomplets vu la complexité
et la rapidité des ARM 32 bits, ce qui rend la chose difficile.

Le microcontrôleur simulé est précisément un STM32F407, fabriqué par la société franco-italienne
ST-Microelectronics, qui fait partie de la famille STM32F4, et équipe les cartes Olimex E-407 et
Discovery STM32F407.

