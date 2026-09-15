# installation d'une application de facila
```
téléchargez les fichiers à partir de github
  - depuis facila/install : facila_install.sh , commande Download
  - depuis facila/APPLI : commandes Code + Download ZIP  

l'installation se fait dans le répertoire de l'utilisateur
tapez les commandes suivantes :
  DIR="nom du répertoire où se trouvent les fichiers téléchargés"
  APPLI="nom de l'application à installer"
  TAR="nom du fichier de l'application $APPLI.vx.xx.tar.gz
  ZIP=$APPLI-main.zip
  cd
  mv $DIR/facila_install.sh .
  mv $DIR/$ZIP .
  unzip $ZIP
  sh facila_install.sh $TAR
  rm facila_install.sh

si dependance

si la variable globale $FACILA n'existe pas
- elle est créée dans ~/.bashrc : "export FACILA=~/facila"

si old

proc_init_data
proc_init_lang
proc_save_new
proc_command
```
