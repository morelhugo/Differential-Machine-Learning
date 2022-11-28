# Differential-Machine-Learning

DIFFERENTIAL MACHINE LEARNING
RAPPORT D’UNE APPROCHE DISRUPTIVE DE L’ÉVALUATION D’OPTIONS ET DE LEURS DÉRIVÉES
MOREL Hugo, NGO Olivier et PIACENTINO Léo Machine Learning in Finance | ENSAE 2020-2021
 
 «The unreasonable effectiveness of what we called ’differential machine learning’ permits to accurately train ML models on a small number of simulated payoffs, in real-time, suitable for online learning. Differential networks apply to real-world problems, including regulations and risk reports with multiple scenarios. Twin networks predict prices and Greeks with almost analytic speed, and their empirical test error remains of comparable magnitude to nested Monte-Carlo. » - Antone Savine and Brian Huge. Differential Machine Learning. arXiv:2005.02347v4. January 2020 (updated in October 2020).
«Standard one-sided bump-and-recalculate [Monte-Carlo] would take about half an hour. Bad. However, with automatic adjoint differentiation, you get the same numbers – to the 8th decimal – in a few seconds. » - Rolf Poulsen. This Is Not Sparta: A Joint Effort. WILMOTT Magazine, p.36-37. 2018.
 1

Table des matières
1 2 3
4
5
6 7 8 9
Introduction ....................................................................................................................... 3 Revue de la littérature ....................................................................................................... 4 Théorie et implémentation ................................................................................................ 4
3.1
3.2
3.3
3.3.1 3.3.2 3.3.3
Réseaux de neurones et AAD............................................................................................... 4
Differential Machine Learning............................................................................................ 7
Implémentation, de la théorie à la pratique ....................................................................... 9
Graphiques d’évaluation...................................................................................................................9 Éléments constitutifs atomiques ..................................................................................................... 10 « The Tape »...................................................................................................................................10
Résultats principaux et applications ............................................................................... 11
4.1
4.2
4.2.1 4.2.2
Présentation et commentaires des résultats principaux du papier ................................ 11
Applications......................................................................................................................... 12
Option Digitale ............................................................................................................................... 12 Extension : Gamma ........................................................................................................................ 13
Apports de l'article........................................................................................................... 14
5.1 Point de vue scientifique/théorique ................................................................................... 14
5.2 Point de vue pratique/professionnel..................................................................................14
Discussion et critiques ..................................................................................................... 14 Conclusion ....................................................................................................................... 15 Références........................................................................................................................ 16 Annexe ............................................................................................................................. 17
