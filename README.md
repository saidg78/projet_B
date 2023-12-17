Le but du projet est de créer un système capable de compter des composants électroniques en se basant sur la reconnaissance et la classification d'images. Ce dispositif utilise une carte Arduino Nano 33 BLE et une caméra OV7670.

Les objectifs spécifiques du projet sont les suivants :

Créer un modèle de Deep Learning capable de reconnaître les composants électroniques.
Intégrer le modèle de Deep Learning sur la carte Arduino Nano 33 BLE.
Activer la connexion BLE sur la carte Arduino Nano 33 BLE.
Envoyer les données par BLE vers Node-RED.
Créer un tableau de bord interactif dans Node-RED pour afficher les données.
Étapes du projet

Le projet se déroulera en plusieurs étapes :

Préparation des données
La première étape consiste à préparer les données pour l'entraînement du modèle de Deep Learning. Cela comprend la collecte d'images des composants électroniques à reconnaître. Les images peuvent être collectées à l'aide d'une caméra ou d'une source d'images existante.

![image](https://github.com/saidg78/projet_B/assets/148437845/9199cc1c-4312-490d-8ecf-6256680ce348)


Entraînement du modèle
La deuxième étape consiste à entraîner le modèle de Deep Learning sur les données préparées. Cela peut être fait à l'aide d'un framework de Deep Learning tel que TensorFlow ou PyTorch. Dans la situation actuelle et suite a l'utilisation de l'Arduino 33BLE qui a des capacités limités, je vais utiisé le TensorFlow Lite.
![image](https://github.com/saidg78/projet_B/assets/148437845/d67014b9-a8e3-496f-a39e-a954f4fa825d)


Intégration du modèle sur la carte Arduino
La troisième étape consiste à intégrer le modèle de Deep Learning sur la carte Arduino Nano 33 BLE. Cela peut être fait en utilisant la bibliothèque telechargé de chez Edge Impulse.
![image](https://github.com/saidg78/projet_B/assets/148437845/4f070eff-1392-4cd1-b08b-8831c4803b63)


Activation de la connexion BLE
La quatrième étape consiste à activer la connexion BLE sur la carte Arduino Nano 33 BLE. Cela peut être fait en utilisant la bibliothèque Arduino BLE.

![image](https://github.com/saidg78/projet_B/assets/148437845/08cbd158-83c8-4a8a-868c-a0ce48191f56)


Envoi des données par BLE
La cinquième étape consiste à envoyer les données par BLE vers Node-RED. 

![image](https://github.com/saidg78/projet_B/assets/148437845/d1fb73b4-fc1a-45cc-8beb-991906f88c9d)
![image](https://github.com/saidg78/projet_B/assets/148437845/73e506ee-41c6-4b02-bef5-8ada8b902f91)



Création du tableau de bord
La sixième et dernière étape consiste à créer un tableau de bord interactif dans Node-RED pour afficher les données. Cela peut être fait en utilisant les nodes Node-RED appropriés
