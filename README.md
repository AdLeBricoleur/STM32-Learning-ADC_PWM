# STM32-Learning-ADC_PWM
Ce dépôt correspond à mon apprentissage de l'ADC et de l'UART TX sur STM32L476RG.

Je travaille sur un Nucleo-L476RG.

Pour connaître la configuration des Horloges et des Pinouts, il faut afficher le fichier .ioc sur CubeMX.

Ensuite, j'ai codé dans le fichier Core/Src/main.c. J'utilise l'IDE CubeIDE.

J'ai noté mes observations dans le Dossier Compte_Rendu.

Le but de cette manipulation est de moduler la PWM en fonction d'un pontentiomètre connecter à l'ADC.

J'avais plusieurs objectifs :
- Faire cette manipulation en "polling"
- Faire cette manipulation en Interruption
- Faire cette manipulation avec un DMA sur l'ADC
