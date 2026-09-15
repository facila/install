# installation d'une application de facila

téléchargez facila_install.sh à partir de github :
- cliquez sur : Code
- cliquez sur : Download ZIP

téléchargez l'application à installer à partir de github :
- cliquez sur : Code
- cliquez sur : Download ZIP

l'installation se fait dans le répertoire de l'utilisateur
tapez les commandes suivantes :
  APPLI=sxabloni
  MAIN=$APPLI-main
  TAR=$APPLI.vx.xx.tar.gz
  DIR="nom du répertoire où se trouve le fichier téléchargé : $MAIN.zip"
  cd
  mv $DIR/$MAIN.zip .
  unzip $MAIN.zip
  sh $MAIN/install.sh $TAR

si la variable globale $FACILA n'existe pas
- elle est créée dans ~/.bashrc : "export FACILA=~/facila"
