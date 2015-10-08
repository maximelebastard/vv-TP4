V&V TP 4
====

Maxime Lebastard
---

TP de tests de requetes

Question sur les résultats JMeter
---
Les tests ont été une réussite sur le plan de la tenue en charge du serveur, car toutes les requêtes ont renvoyé une réponse en code 200.
En revanche, comme indiqué sur le Graph jMeter, le délai de réponse moyen est d'environ 1700 ms, ce qui est bien supérieur aux 30ms requises dans l'assertion. Il faudrait donc optimiser le temps de réponse, par la mise en place d'un cache ou d'un load balancer par exemple.