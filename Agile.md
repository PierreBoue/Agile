# Gestion de projet Agile   
## Glossaire Agile
- **Daily Meeting :**   
ou standup daily meeting
point quotidien sur l’évolution de l’itérattion en cours en se posant 3 questions :
   - Qu’est-ce que j’ai fait hier ?
   - Quelles difficultés j’ai rencontré ?
   - Qu’est-ce que j’ai prévu de faire aujourd’hui   
    
- **Planning Poker :**   
ou scrum poker   
plannification de l’itération en estimant la difficulté de chaque tâche, avec toute l’équipe le scrum master et le product owner. Chaque membre de l’équipe vote, sous forme d’un jeu de carte, pour déterminer la charge de travail estimée pour la tâche    
    

- **Product Backlog :**
Liste des spécifications demandées par le client avec une estimation de la complexité et de la valeur métier, pour pouvoir classer cette liste.
    
   
- **Product Owner :**   
Représentant du client en charge de veiller à ce que les spécifications demandées soient respéctées. Il est soit employé par le client soit par l'équipe de dev
    

- **Release :**   
Livrable objectif de chaque sprint    
     

- **Scrum Master :**   
Animateur, coach garant du respect de la méthodologie au cours des retrospectives
   

- **Sprint :**   
Itération Agile constituée de toutes les étapes : planification, production, standup daily meeting, revue, retrospective
    

- **Sprint Planning :**   
Liste des étapes du sprint avec leur chronologie   
    

- **Sprint Review :**    
Comparaison entre les objectifs du sprint et le release obtenu. Présentation et validation du release obtenu par le client ou à défaut le product owner. Calcul de la vélocité en additionnant les points d’estimation associés aux livrables validés.
    

- **Rétrospective :**
À la lumière du résultat de la revue, correction des objectifs du prochain Sprint en tenant compte de ce qui a posé problème et de ce qui reste à valider
    

- **User Story :**   
courte description d’une fonctionnalité à livrer au client. Courte et ciblée elle doit être indépendante d’autre fonctionnalités. L’équipe de développeur peut négocier son contenu. Elle doit porter une valeur métier
    

- **Valeur métier :**   
Estimation de la valeur qu’offre une fonctionnalité pour répondre au besoin client
    

- **Vélocité :**    
rapport entre la complexité prévue pour effectuer des tâches et la complexité réelle

## Diagram

![diag](Gestion%20de%20produit%20Agile.drawio.png)

## Descriptif   

### Spécifications   

Dans un premier temps il faut définir précisément les spécifications, le client fournit une description du projet souhaité. Avec les questions de l'équipe, le product owner demande au client de préciser les spécifications qui ont besoin d'être éclaircies.

### Stratégie   

Les spécifications sont découpées en user stories. Chaque user story reprend les points suivants:

- Titre : en tant que ... je veux ...
- Critère d'accepatation : pour que ma story soit validée il faut que ...
- Valeur métier : à quel point cette story a de l'importance pour le client ? représenté par un chiffre arbitraire
- Comlexité : Quel effort est nécessaire à l'équipe pour mener à bien cette story ? représenté par un chiffre arbitraire qui reflète la complexité relative des différentes stories. Le chiffrage se fait de manière collègiale avec toute l'équipe   

   
L'ensemble des stories constitue le product backlog.

#### Sprint

Il se divise en plusieurs étapes :

1 - planification :

Un certain nombre de stories à réaliser sont prévues au début de chaque itération de façon à ce que la somme des complexité corresponde à la vélocité de l'équipe et à privilégier les stories qui ont le plus de valeur métier. La vélocité est le nombre de complexité réalisable en une itération. À la première itération la vélocité est determinée arbitrairement. Aux itérations suivantes la vélocité et réajustée en fonction des résultat des itérations précédentes.
   
2 - daily meeting ou standup daily meeting :

réunion quotidienne où tout le monde se pose les questions suivantes :
 - qu'est-ce que j'ai fait hier ?
 - quelles sont les difficultés que j'ai rencontrées ?
 - qu'est-ce que j'ai prévu de faire aujourd'hui ?
On peut ajuster le sprint pour s'assurer d'atteindre l'objectif de l'itération en fonction des conclusions de ce meeting.

3 - Production :

Les équipes développent ce qui est nécessaire pour valider les stories qui leur sont affectées.
   
4 - Revue :

Livraison des stories terminées. Les auteurs présente les nouvelles fonctionnalités qu'ils ont créées au cours du sprint. Le product-owner et dans l'idéal le client valident les stories qui respectent les critères d'acceptation

5 - Rétrospective :

Un bilan comparatif entre les objectifs et les résultats obtenus permet de tirer des conclusions sur la vélocité réelle, les erreurs à corriger, quelles sont les stories non-faites ou pas terminées et comment réctifier le tir pour la prochaine itération.

 On repart ensuite sur l'itération suivante à l'étape 1
 
Si c'est la dernière itération on livre le produit fini au client.
Le scrum-master, qui est soit un membre de l'équipe de dév soit une personne uniquement affecté à cette tâche préside et anime les différentes réunion pour s'assurer qu'elles atteignent leurs objectifs. Il est également le porte-parole de l'équipe auprès du product-owner et du client.