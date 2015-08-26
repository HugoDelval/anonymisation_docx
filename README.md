# Présentation

Ce projet permet de flouter les images d'un docx. Il est utilisable en standalone (fichier *doc_a_anonymiser*) ou via une application Django.

# Utilisation
## Commande

	./anonymiser_images_docx.py -i <chemin du docx a anonymiser> -o <repertoire du docx final> [-b <rayon du blur pour flouter les image>=17]

## Exemple
	./anonymiser_images_docx.py -i doc_a_anonymiser/Sample.docx -o doc_anonyme/ -b 20
