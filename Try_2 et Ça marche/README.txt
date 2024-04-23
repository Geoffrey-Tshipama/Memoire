Bonjour chers tous

Voici les codes et les différentes entrées qu'on peut utiliser pour ce code
L'idée générale ici est d'avoir une application ou script python qui soit capable de détecter toutes les classes possibles de l'algorithme YOLOv8 pré-entrainé (yolov8n.pt) dans une série d'images ou une vidéo et de suivre leur position au cours des autres vidéos

Nous avons 3 fichiers .py dont :
helper.py : qui a une fonction qui prend un fichier vidéo et return une autre fichier vidéo
objet_detection.py : détecte les objets
objet_detection_tracking : détecte et suit les objets.