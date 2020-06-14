## Universalité de la machine de Turing et système distribuée

Alan Turing a fait de l’informatique une science en créant un modèle d’ordinateur universel: la machine de Turing.  
=> Tout ce qui peut être calculé par un algorithme le peut par cette machine.  
=> les ordinateurs sont construits suivant ce modèle universel.  
=> Cela permet, tout en profitant de la puissance d’un ordinateur, de s’affranchir des détails technologiques de son architecture pour apprivoiser les algorithmes _On y gagne en abstraction : la technologie exécutrice de l'algorithme ne nous importe pas_ 
=> Ces algorithmes peuvent ainsi être conçus et analysés à partir de principes abstraits rigoureux, puis testés concrètement sur n’importe quelle machine universelle donnée, avant d’être déployés sur une autre. Cette universalité nous a permis d’espérer un monde algorithmique sans erreurs.

! L'universalité de la machine de Turing est perdue dès lors qu'on utilise un ensemble de machine afin d'augmenter la robuteste du système d'information. Il faut choisir entre l'universalité de la machine de Turing et la robutesse avec l'efficacité.  

_La perte de l’universalité de Turing implique que l’on ne peut pas déployer sur un réseau de machines, un algorithme conçu à partir de principes abstraits issus de l’algorithmique classique, centralisée, ou testé sur d’autres machines, et s’attendre à ce que l’algorithme fonctionne de la même manière. Les détails technologiques du réseau entrent en jeu : l’abstraction et la rigueur en pâtissent._





- Machine de Turing : on s'abstrait de l'implémentation de la machine exécutant l'algorithme  
- Système distribué : nous sommes obliger de prendre en compte l'architecture (donc l'implémentation du réseau) pour créer un algorithme.  






