Options 1: 

1- J'ai construit mon image en local

![Screen Shot 2024-11-17 at 15 12 38](https://github.com/user-attachments/assets/5851b838-5e0c-4349-abe5-b8d54e2a1cbb)


2- hebergement sur mon dockerHub

![Screen Shot 2024-11-21 at 13 34 19](https://github.com/user-attachments/assets/3163a1f0-0407-40f5-ae75-01e6c5714421)


3- Pour le déploiement, j'ai utilisé Azure Container App. Les étapes du déploiement sont les suivantes:
	* Création d'un compte étudiant sur Azure (Après cette étape on aura accé à un certain nombre de service azure dont la création d'un app container)
	* Crétion d'un app container : lors de la creation de l'app container on est amené à renseigner un bon nombre de paramètre le plus important est 
 		la spécification de l'image qui se trouve dans mon dockerhub pour permettre à Azure d'y aller et déployer mon image << diagne48/cloud:latest >>.
	 	Si la version n'est pas spécifié, il prendra la dernière version.
	![Screen Shot 2024-11-17 at 16 30 52](https://github.com/user-attachments/assets/23d45911-5207-4216-99f2-c4d9f5ec4285)

Note: Do it in 3 separated jobs.
