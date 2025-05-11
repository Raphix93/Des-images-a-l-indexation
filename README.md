# README - Des images à l'indexation : application de methodes de detection d'objets à un fonds photographique d'archives patrimoniales

Validation du cours - 32M7138 : "Du pixel aux images : introduction au traitement des images 2D"

Raphaël Rollinet (raphael.rollinet@unine.ch) 
Université de Neuchâtel (mobilité*)
Master en Patrimoine régional et humanités numériques
Printemps 2025 - Université de Genève*
Sous la direction de Adrien Jeanrenaud

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

