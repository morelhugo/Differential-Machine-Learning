# Differential-Machine-Learning

L’article étudié ici, « Differential Machine Learning »1, a été écrit en Janvier 2020 et publié sous arXiv.org (site de l’université de Cornell) par Antoine Savine et Brian Huge (Chief Analysts) deux chercheurs de l’équipe « Superfly analytics » à Danske Bank et docteurs en mathématiques, diplômés de l’université de Copenhague. Remarquons qu’il semblerait que ce sujet soit essentiellement traité ou tout du moins géré par Antoine Savine. En effet, le sujet traité par l’article est le domaine de recherche de ce dernier, l’«Automatic Adjoint Differentiation »2, dite AAD. En témoignent :
- son livre : Modern Computational Finance: AAD and Parallel Simulations.
- son cours à King’s college : https://nms.kcl.ac.uk/probability/workshopPages.php?id=8

L’article traite d’une technique combinant Machine Learning et la différentiation automatique adjointe (AAD), donnant le Machine Learning différentiel (DML). Le DML combine des techniques de « Deep Learning » et des méthodes d’analyse numérique (AAD). La «
« Différentiation Adjointe » (AD) est basée sur le Théorème de Dérivation des Fonctions Composées ou « Chain-rule ». L’AD peut être vue de deux manières différentes : en avant ou à l’envers. Il s’avère que l’AD à l’envers n’est ni plus ni moins que la notion de back- propagation dans les réseaux de neurones. Les auteurs défendent la thèse selon laquelle cette technique novatrice est particulièrement rapide et précise pour résoudre des problèmes d’optimisation variés ; notamment en finance de marché et plus particulièrement en évaluation d’option et des « grecques ». Les résultats présentés sont objectivement impressionnants. En effet, il s’avère que le DML est plus rapide et efficace que les méthodes classiques de Monte- Carlo et différences finies. Les résultats présentés sont soutenus par des théorèmes dont les essais de la preuve3 sont donnés dans l’article. De plus, les auteurs présentent l’intérêt de leur travail dans un cadre professionnel, tant pour des problématiques d’évaluation, de gestion de risque (grecques), de réajustement de valeurs (XVA), etc...

Dans ce rapport, nous commenceront par une revue de la littérature pour faire un état des lieux du sujet. Ensuite, nous expliciterons la théorie derrière l’article pour pouvoir appréhender les apports de l’article dans les mondes scientifiques et professionnels. Ainsi, nous pourrons présenter les résultats trouvés dans l’article ainsi que ceux de notre implémentation de la procédure. Pour finir, nous apporterons une discussion et une critique constructive du sujet.


# Project' Architecture

## Report :
  PDF : Report Differential Machine Learning.pdf
  
## Presentation :
  LaTex report : Presentation Differential Machine Learning
