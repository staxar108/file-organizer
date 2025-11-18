# ==============================
# 🗂️ File Organizer - Python
# ==============================

# Description
# Ce script organise automatiquement tous les fichiers d’un dossier
# en créant des sous-dossiers par type (images, vidéos, documents, audio, archives, etc.)

# ==============================
# Fonctionnalités
# ==============================
# - Analyse du dossier fourni
# - Classement automatique selon l’extension
# - Création automatique des sous-dossiers nécessaires
# - Déplacement sécurisé des fichiers
# - Catégories personnalisables
# - Compatible Windows / Linux / macOS

# ==============================
# Installation
# ==============================
# Prérequis : Python 3.x
# Cloner le dépôt :
#   git clone https://github.com/votre-nom/file-organizer.git
#   cd file-organizer

# ==============================
# Utilisation
# ==============================
# Lancer le script :
#   python file_organizer.py
# Le programme demandera :
#   "Veuillez entrer le chemin du dossier à organiser :"
# Entrer le chemin complet et laisser le script organiser les fichiers.

# ==============================
# Exemple d’organisation
# ==============================
# Avant :
#   photo.png
#   musique.mp3
#   archive.zip
#   document.pdf
#   video.mp4
#   random.exe
#
# Après :
#   Images/photo.png
#   Audio/musique.mp3
#   Archives/archive.zip
#   Documents/document.pdf
#   Vidéos/video.mp4
#   Autres/random.exe

# ==============================
# Personnalisation
# ==============================
TYPES = {
    "Images": [".png", ".jpg", ".jpeg", ".gif"],
    "Vidéos": [".mp4", ".mkv", ".avi"],
    "Documents": [".pdf", ".docx", ".txt"],
    "Audio": [".mp3", ".wav"],
    "Archives": [".zip", ".rar", ".7z"],
}

# ==============================
# Erreurs courantes
# ==============================
# RuntimeError: input(): lost sys.stdin
# -> Se produit si le script est lancé sans terminal
# -> Solution : lancer via CMD / PowerShell / Terminal

# ==============================
# Licence
# ==============================
# MIT License
# Copyright (c) 2025 [Votre Nom]
# Permission is hereby granted, free of charge, to any person obtaining a copy
# of this software and associated documentation files...

# ==============================
# Support
# ==============================
# Si ce projet vous aide, laissez une étoile ⭐ sur GitHub
