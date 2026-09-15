# installation d'une application de facila
```
téléchargez les fichiers à partir de github
  - depuis facila/install : facila_install.sh , commande Download
  - depuis facila/APPLI : commandes Code + Download ZIP  

l'installation se fait dans le répertoire de l'utilisateur
tapez les commandes suivantes :
  DIR="nom du répertoire où se trouvent les fichiers téléchargés"
  APPLI="nom de l'application à installer"
  TAR="nom du fichier de l'application sxabloni.v1.00.tar.gz
  MAIN=$APPLI-main
  cd
  mv $DIR/$MAIN.zip .
  unzip $MAIN.zip
  sh $MAIN/facila_install.sh $TAR

si la variable globale $FACILA n'existe pas
- elle est créée dans ~/.bashrc : "export FACILA=~/facila"
```
