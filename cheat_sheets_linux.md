# Cheat sheets linux / Terminal  

## Commande de base  
  
Fermer le terminal : exit  
nettoyer le terminal : clear  
annuler : Ctrl + C  
Commande précédente / suivante : flêche bas / haut  
Ouvrir le manuel : man man  
ouvrir le manuel pour la commande : man (nom commande)  
  
## Se déplacer
  
Changer de répertoire : cd (nom)  
retourner sur HOME : cd  
Retourner dans le dossier parent : cd ..  
Retourner dans le dossier précédent : cd -  
Connaitre son emplacement : pwd  
  
## Afficher les dossiers/fichiers  
  
affichez le contenu du répertoire actuel : ls  
affichez le contenu du répertoire + fichers cachés : ls -a  
affichez les permissions : ls -l  
affichez les dossiers cachés et les permissions ls -la   
emunérer tout les fichiers dans les sous-répertoires : ls -R  
ouvrir un fichier : nano (nom)   
affichez le fichier : cat (nom)  
ouvrir sur vs code : code .  
  
## Suppression  
  
supprimer un répertoire vide : rmdir (nom)  
supprimer un répertoire : rm -r (nom)  
supprimer un répertoire plein : rm -rf (nom)  
supprimer un fichier : rm (nom)  
supprimer un fichier de force : rm -f (nom)  
  
## Création 
  
Créer un répertoire : mkdir (nom)  
Créer un fichier : touch (nom)  
Déplacer un fichier : mv (nom) (répertoire de destination)  
renommer un fichier : mv (ancien nom) (nouveau nom)  
copier un fichier : cp (nom) (répertoire de destination)  
copier un répertoire : cp -r (répertoire à copier) (répertoire de destination)  
  
## Recherche  
  
Rechercher un fichier/répertoire : find (répertoire) -name (nom)  
Rechercher dans le répertoire actuel : find. -name (nom)  
Rechercher du texte dans un fichier : grep (mot) (nom du fichier)  
Localiser un fichier : locate (nom)  
  
## Permissions  
  
Effectuer une tache demandant une autorisation : sudo (commande)  
  
## Gérer le texte  
  
Visualiser les premières lignes d'un fichier : head (nom)  
Visualiser les dernières lignes d'un fichier : head -n (nombre) (nom)  
comparer le texte de deux fichiers : diff (nom du fichier 1) (fichier 2)  
ajouter des données à un fichier : echo (données) >(nom)  


