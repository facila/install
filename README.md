# installation d'une application de facila
```
Téléchargez les fichiers à partir de github
  depuis facila/install : facila_install , commande Download
  depuis facila/APPLI   : commandes Code + Download ZIP  

L'installation se fait par défaut dans le répertoire de l'utilisateur

Tapez les commandes suivantes :
  bash "chemin"/facila_install FICHIER_TAR

Opérations réalisées lors de l'installation par le script :
  si install_check : vérification des dépendances 
  si la variable globale $FACILA n'existe pas : création dans ~/.bashrc de : "export FACILA=~/facila"
  si ancienne version , elle est sauvegardée dans $FACILA/save/old ( avec facila_$APPLI si il existe , sinon avec $APPLI )
  si $APPLI/var/fr_FR.UTF-8 et $LANG est différent de fr_FR.UTF-8 : copie du dossier en $LANG pour traduction 
  sauvegarde de $ZIP dans $FACILA/save/install
  sauvegarde de $TAR dans $FACILA/save/version
```
