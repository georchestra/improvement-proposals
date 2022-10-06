# Propositions d'évolutions de geOrchestra

## Principes

Un des rôles du PSC est de prendre des décisions quant au management du projet. Cela peut inclure, sans être exhaustif :

- les modalités d’animation de la communauté
- la communication
- les modifications au code source et ayant un impact significatif sur sur une partie de la communauté, ou affectant la compatibilité ascendante, ou affectant la compatibilité avec des produits tiers
- les modalités de contribution au code source
- le fonctionnement du PSC

Le PSC est constitué d’individus impliqués dans le projet. Ces individus ne représentent aucune structure. Un effectif impair permet de faciliter le processus de vote.


## Processus

1. Toute personne peut faire une proposition (GeOrchestra Improvement Proposal, ci-après désigné GIP), à titre individuel ou en représentant une organisation. La GIP doit être rédigée dans la langue native de la personne et postée sur le canal de la communauté. Si cette langue native n’est pas l’anglais, la traduction de la GIP en anglais doit également être fournie.


2. Il est conseillé que la GIP suive cette structure afin de faciliter son examen et son adoption :
  - l’objectif visé
  - les bénéfices attendus pour la communauté
  - les modalités d’implémentation
  - les risques éventuels et le moyen de les couvrir


3. Toute personne est invitée à examiner la GIP, poser des questions, proposer des modifications sur le canal de la communauté. La personne qui a déposé la GIP peut prendre ces modifications en compte en modifiant la GIP sur le dépôt de sources. Les modifications sont historisées.


4. Lorsque la personne pense la GIP prête à être soumise, elle demande au PSC de se prononcer. Le PSC annonce sur le canal de la communauté qu’un processus de vote commence.


5. Chaque membre du PSC a 15 jours (360 heures à compter de la date de l’annonce du vote) pour se prononcer, à compter de l’annonce du vote. Pour ce faire, il ajoute son vote à la GIP publiée sur le dépôt de sources, avec :

  - `+1` : signifie que le membre supporte la GIP
  - `+0` : Moyennement pour, avec indication favorable
  - `0` : Moyennement pour
  - `-0` : Moyennement contre, avec indication défavorable
  - `-1` : Contre, avec motifs détaillés


6. Un vote est définitif.


7. A la fin de la période, les membres du PSC qui ne se sont pas prononcés votent automatiquement avec +0.


8. Si tous les membres du PSC ont voté, la période prend fin immédiatement.


9. Tout membre du PSC peut demander une extension de 15 jours (360 heures) tant que la période n’est pas écoulée. La période ne peut être rallongée qu’une fois.


10. Tout membre du PSC qui vote `-1` contre une GIP doit fournir publiquement des explications sur les raisons de son vote.


11. Si la GIP recueille au moins 30% de `+1` rapporté à l’effectif du PSC, ET si elle ne recueille aucun `-1`, elle est acceptée. L’ensemble du processus de vote est archivé et reste public.


12. Si la GIP recueille au moins 30% de `+1` ET un ou plusieurs `-1`, elle est placée en attente. Tous les membres du PSC ayant voté `-1` doivent proposer sous deux mois une alternative rendant la GIP acceptable. Le porteur du GIP est alors libre de modifier sa proposition puis de demander un nouveau processus de vote qui reprend au début, avec numéro d’identification mineur.


13. Aucune GIP contrevenant sensiblement au manifeste ne peut être acceptée. Si une telle GIP se présente, les membres du PSC ne sont pas tenus de proposer une alternative.


14. Si la GIP recueille au moins 30% de +1 ET un ou plusieurs -1, et si aucun membre du PSC ayant voté -1 ne fait de proposition sur une alternative rendant la GIP acceptable, la GIP est acceptée.


15. Une GIP ne peut être proposée plus de trois fois. Si par trois fois la GIP n’est pas acceptée, ou si elle n’est pas reproposée après elle est refusée.
