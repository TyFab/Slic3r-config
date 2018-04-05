Slic3r settings

Fichiers de configuration pour Slic3r utilisé pour les machines du TyFab.
Instructions

    Effacer la configuration actuelle avant de copier ce dépôt :

    rm -rf ~/.Slic3r-old/
    mv ~/.Slic3r/ ~/.Slic3r-old/

    Récupérer ce dépôt dans ~/.Slic3r :

    git clone https://github.com/TyFab/Slic3r-settings.git ~/.Slic3r

    Mise à jour :

    cd ~/.Slic3r
    git pull

    Avant de partager vos modifications, vérifier que les paramètres fonctionnent parfaitement, et faire : git diff et git status

    Ensuite, envoyer vos modifications :

    git add -A
    git commit -A


