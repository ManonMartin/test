---
title: Aide analyses données protéomiques publiées
date: 202403
contact: Oksana Savel <oksana.savel@uclouvain.be>
institute: LIBST
unit: BNTE
pi: Melissa Page
data: proteomics
analysis:
leader: MMA
service: analysis
summary: |
  
---

# notes

Leuven: 

Sacramento

# Mail Oksana - 24/03/01

Bonjour Manon, 

Je voudrais extraire des données de deux jeux de données protéomiques (comparant des cerveaux KF à 2 ou 3 âges différents) pour obtenir un graphe similaire à celui-ci pour quelques protéines d'intérêt dans mon projet :
image.png
Ce graphe vient de l'article suivant : https://doi.org/10.1111/acel.13689. Mais je ne comprends pas vraiment comment ils ont fait en lisant leurs matériel et méthodes peu détaillé. 
Ils ont utilisés pour cela le jeux de données "MZM_sacramento_Proteomics_dataset" (de l'article dans le pdf "Proteomics_sacramento") ci-joint. 

J'ai parlé avec Hervé Degand de ce jeu de données mais il y a quelque chose qu'on ne comprend pas trop; en bleu et rouge, ils highlightent tout ce qui est down/upregulé significativement. Cependant, quand on regarde leurs colonnes P.Value et adj.P.Value; pas mal de données sont beaucoup plus grandes que 0,05. Donc on ne comprend pas pq c'est significatif. 
Et ici, je ne vois pas trop de quelle donnée partir pour obtenir un graphe similaire à celui-ci dessus.

Pour l'autre jeu de données (GRZ_Leuven_Proteomics et le pdf associé); 
Hervé me disait que je pouvais utiliser les colonnes LFQ intensity des différents réplicats des deux âges pour faire un graphe. Mais je remarque que lorsqu'on regarde la comparaison des moyennes LFQ pour chaque âge, même si c'est significatif (selon l'article + j'ai vérifié dans JMP); les valeurs sont très similaires (24,29 +/- 0,36 et 24,8 +/- 0,16). Du coup ça me pose question si c'est vraiment correct de faire ça? Est-ce qu'on doit pas s'attendre à des valeurs plus éloignées ou est-ce que c'est normal d'avoir des écarts faibles?

Est-ce que tu pourrais m'aider dans cette analyse ? 
On peut en parler si c'est plus facile; la semaine prochaine, je suis disponible le mardi et le vdd peu importe quand; les autres jours je donne TP donc c'est un peu plus compliqué mais je peux trouver un moment.
