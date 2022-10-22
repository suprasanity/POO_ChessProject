# Configuration

in the src/main/resources/application.properties, find the following lines:

```properties
camel.component.jms.connection-factory.user=
camel.component.jms.connection-factory.password=
```

and set the properties provided in class.g



Protocole Réseau :

On se passe les mouvements des pièces que l’on joue 

Quand on met son adversaire en échec on lui dit échec pareil pour échec et mat.


Quand on gagne la partie on envoie loose à l’adversaire nul en cas de nul .

Règles :

Règle d'échec classique + ajout de missions :
	
pas bouger la dame
pas manger de cavalier 
pas de rock
faire 2 echec
manger la reine ennemie
promouvoir un pion (quand elle arrive sur la dernière ligne ennemi
pas bouger le roi jusqu'à l'échec
manger tous les pions 
gagner la partie avec le moins de pièce
ne pas perdre ces 2 tours

Gagner une partie rapporte 80 points et chaque mission rapporte 10 points
Pour remporter la victoire on fait la comparaison des points de chaque joueur
