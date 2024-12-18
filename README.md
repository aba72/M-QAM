# M-QAM
Diagramme de Constellation QAM  Ce script Python génère et affiche le diagramme de constellation pour des modulations QAM (Quadrature Amplitude Modulation) de différentes tailles. Il inclut également un tableau détaillé des symboles avec leurs caractéristiques (énergie, phase, etc.)

Fonctionnalités principales :

    Génération de constellations QAM : Les constellations de tailles standard (4, 16, 32, 64, 128, 512, 1024, 2048, 4096) sont supportées.
    Exclusion de points : Certaines configurations excluent des points pour des tailles spécifiques (ex. : QAM-32).
    Diagramme interactif : Les symboles inclus et exclus sont affichés avec des couleurs distinctes (jaune et rouge).
    Centre personnalisé : La constellation est centrée sur un symbole défini par l'utilisateur.
    Tableau des symboles : Génération d'un tableau indiquant les coordonnées (I, Q), l'énergie, et la phase de chaque symbole.

Utilisation :

    L'utilisateur entre la taille de la constellation QAM (ex. : 64-QAM).
    L'utilisateur fournit un symbole de déclenchement pour centrer la constellation (ex. : 0,0).
    Le script génère :
        Un diagramme de constellation.
        Un tableau détaillé des symboles affiché en blocs pour faciliter la lecture.
