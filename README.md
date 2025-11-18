# File Organizer
Organise automatiquement les fichiers d'un dossier en sous-dossiers par type.

# Description
Ce script prend le chemin d'un dossier et classe tous les fichiers qu'il contient
dans des sous-dossiers selon leur type : images, vidéos, documents, audio, archives, etc.

# Fonctionnalités
- Analyse tous les fichiers d'un dossier donné
- Classement automatique selon l'extension
- Création automatique des sous-dossiers
- Déplacement sécurisé des fichiers
- Catégories modifiables dans le code


# Utilisation
Lancer l'executable
Ensuite, entrer le chemin complet du dossier à organiser quand le programme le demande.
Le script s'occupera de tout organiser automatiquement.

# Exemple
Avant :
photo.png
musique.mp3
archive.zip
document.pdf
video.mp4
random.exe

Après :
Images/photo.png
Audio/musique.mp3
Archives/archive.zip
Documents/document.pdf
Vidéos/video.mp4
Autres/random.exe

# Personnalisation
TYPES = {
    "Images": [".png", ".jpg", ".jpeg", ".gif"],
    "Vidéos": [".mp4", ".mkv", ".avi"],
    "Documents": [".pdf", ".docx", ".txt"],
    "Audio": [".mp3", ".wav"],
    "Archives": [".zip", ".rar", ".7z"],
}


# Support
Si ce projet vous aide, laissez une étoile ⭐ sur GitHub
