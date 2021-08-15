# Contexte du projet
un site d'évaluation de cours en ligne (ou MOOC).
Tout en pensant à la maintenabilité et scalabilité du projet

# But du projet
### Partie 1
| Diagramme à réaliser |
|---|
| Class Diagram |
|Use Case Diagram |
|Activity Diagram|
|Architecture cloud|


# Spécification technique
### topologie cloud
-----------------
- Proposition A

| Avantage  | Inconvéniant  |
|---|---|
| Scalable  | Prix  |

![topologie1](https://github.com/mohamedabcd/ps-1mooc/blob/main/proposition1.png?raw=true)

-----------------
- Proposition B Serverless

![topologie2](https://github.com/mohamedabcd/ps-1mooc/blob/main/proposition2.png?raw=true)
| Avantage  | Inconvéniant  |
|---|---|
| Scalable  | - |
| Prix  | - |
-----------------
### Modèle physique de donnée
![topologie2](https://github.com/mohamedabcd/ps-1mooc/blob/main/MCD.png)



# Spécification fonctionnelle
| visiteur |
|---|
| S'enregistrer sur le site|
| Voir liste de MOOC |
|Voir le détail du MOOC|

| user lambdas (est un visiteur +) |
|---|
| Se login / se logout |
| Ajouter des commentaires|
|Ajouter des commantaires|
|Notez les cours|

| Admin (est un user lambda +) |
|---|
| promouvoir les utilisateurs|
|supprimer des commentaires|
|CRUD MOOC |


### Use case
![usecase](https://github.com/mohamedabcd/ps-1mooc/blob/main/usecase.png?raw=true)

# Conclusion
|la proposition B répond aux éxigences demandées par le client. Tout en étant facile à implémenter, à maintenir et se rendre Scalable. Le budjet pour la mise en place de la proposition B n'est pas énorme sur la durée.   



