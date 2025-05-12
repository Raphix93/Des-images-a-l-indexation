# README - Des images à l'indexation : application de methodes de detection d'objets à un fonds photographique d'archives patrimoniales

Validation du cours - 32M7138 : "Du pixel aux images : introduction au traitement des images 2D"

Raphaël Rollinet (raphael.rollinet@unine.ch) <br>
Université de Neuchâtel (mobilité*) <br>
Master en Patrimoine régional et humanités numériques <br>
Printemps 2025 - Université de Genève* <br>
Sous la direction de Adrien Jeanrenaud <br>

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15382105.svg)](https://doi.org/10.5281/zenodo.15382105)

## Résumé

Ce présent rapport est effectué dans le cadre du cours "Du pixel aux images : introduction au traitement des images 2D". Ce notebook traite de méthodes utilisant de l'intelligence artificielle générative que cela soit avec des modèles de deep learning (apprentissage profond) ou un LLM multimodal appliqué au traitement de l'image.  Cette démarche de recherche me permet d'explorer ces méthodes en l'applicant à mon domaine de spécialisation, soit le patrimoine, plus exactement l'archivistique. Le domaine des archives suisse s'est récemment doté d'un livre blanc sur l'apprentissage automatique dans les archives notamment sur l'indexation en profondeur au service de l'accès aux archives. Mon travail vise à explorer différente méthode et à analyser les résultats obtenus afin d'en faire la critique selon les besoins métiers d'un archiviste. L'objet de la recherche est un fonds d'archives anciennes auquel j'appliquerai des méthodes de détection d'objet. Le résultat de ces détections sera extrait sous forme de fichier CSV comprenant le nom de l'image et le résultat de la détection sous forme de mots-clés. L'objectif est de pouvoir utiliser ces méthodes pour indexer automatiquement le contenu d'un fonds d'images afin d'enrichir la description et donc l'accès documentaire de ces photographies.

## Contenu des données de recherche
Le rendu contient les éléments suivants :

- un README détaillant le contenu du rendu.
- Un dossier "Colab_Notebooks" qui comprend :
    - Un notebook Python faisant office de dossier comprenant le code et le texte sous forme de markdown.
    - Un sous-dossier images, soit les images utilisées pour ce travail (en cas de problème lors de la décompression du fichier, les 18 images sont disponibles directement au lien suivant : https://milvignes.docuteam.cloud/fr/units/1-archives-communales-de-milvignes-1326-2013/gallery)
    - Le dossier "Colab_Notebooks" devra être placé dans votre Google Drive et lié a Google Colab pendant l'exécution du code.
    - Une fois le notebook exécuté, vos résultats seront directement placés dans ce dossier.
- Un dossier "Mes_resultats" comprenant :
    - Un sous-dossier "annoted", contenant les images annotées des détections d'objets.
    - Les fichiers CSV avec les détections d'objet pour chaque image.
    - Un dossier "controle_qualite" contenant une copie des CSV annotés pour vérification des résultats.
- Mention de la licence pour les données de cette étude.

## Prérequis pour la lecture du notebook

- Utilisation de Google Colab pour le notebook
- Déposer le dossier "Colab_Notebooks" dans votre Google drive
- Installer les libraires requises au début de chaque partie de code
- Avoir un compte gratuit Openrouter et générer une clé pour le modèle LLM Llama-4 (https://openrouter.ai/meta-llama/llama-4-maverick:free/api)

