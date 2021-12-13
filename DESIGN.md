# IDM_TP1

Dans le cadre de notre dernière année de Master en ingéniérie logicielle au sein de l'ISTIC, nous avons été aménés à réalisé un DSL pour JSON
pour la matière d'IDM.

### Analyse du méta-modèle

Au cours de notre avancé du premier TP, nous sommes parvenus à nous mettre d'accord sur un méta-modèle regroupant 
selon nous toutes les fonctionnalités demandées étant liées à l'édition mais aussi à la conception d'un ficher JSON.
De ce fait notre méta-modèle comporte d'un coté les commandes principales requises et possibles via les librairies
choisies et de l'autre coté, tous les éléments composant un fichier JSON.
On a conçu le méta-modèle tel qu'un JSON contient une seule expression.
Une expression est soit une entité simple, tel qu'une constante ou encore une expression binaire, soit une entité complexe tel qu'un **JSONObject** ou un **JSONArray**.
Un **JSONArray** contient plusieurs expressions alors qu'un **JSONObject** contient plusieurs objets appelés "keys".
Une 'key' est une string suivie d'une expression.
Ainsi, notre méta-modèle permet d'avoir des tableaux constitués directement de valeurs, et des objets composés de duo clés/valeurs.
