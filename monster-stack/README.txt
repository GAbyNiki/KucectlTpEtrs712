Gabriel Armieux
Théo Royer

Comment Deployé l'appli.


#Se rendre  dans le dossier monster-stack avec les fichier yaml
kubectl apply -k ./

#Recuperer le service avec 
kubectl get services

#Pour avoir l'@IP du site 
minikube service <nomduservice> --url /le nom du service s'appelle monstericon


Comment utiliser l'application

#Aller sur le site avec un navigateur web et rentrer l'adresse ip obtenue précédemet

Il y a un formulaire sur la page du site.
 Il suffit de rentrer un nom dans le formulaire 
et une image seras généré en fonction du nom.

#Pour tous détruire 
kubectl delete -k ./

