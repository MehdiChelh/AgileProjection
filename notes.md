# Outil de projection de cash flows


## Description

Outil open source de projection de cash flow. 

Les enjeux sont les suivants :
- Construire un outil de calcul simple d'utilisation permettant de facilement paralléliser la charge
- Faciliter un développement robuste et agile via des outils connexes :
    - graph de dépendance
    - versioning du code
    - automatisation des tests et des études de sensi
    - visualisation et contrôles des Cash Flows
- Un outil pouvant aussi bien être utilisé par les opérationnels (vision micro et développement) que par le management (vision macro et contrôles)
- Faciliter l'automatisation de la production

L'objectif sera non-seulement de mettre d'avantage l'accent sur l'expérience utilisateur que sur l'optimisation des calculs, mais également de construire un outil s'intégrant d'un framework plus général de calculs actuariels.

L'outil se présentera a priori sous la forme d'une solution hébergée sur des serveurs Linux.


## Architecture

- Core : Framework de projection de cash flow
    - Model = Mesh
        - Mesh = f(Mesh, CashFlow)
        - CashFlow = f(CashFlow, Const, InputPlaceholder)
    - Res = Exec(Mesh, Input)
        - 

##
