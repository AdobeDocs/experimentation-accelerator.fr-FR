---
solution: Journey Optimizer
product: journey optimizer
title: Bonnes pratiques relatives à Journey Optimizer Experimentation Accelerator
description: Améliorer votre capacité à mener des expériences efficacement et à générer des informations
topic: Content Management
role: User
level: Beginner
keywords: contenu, expérience, multiple, audience, traitement
TQID: https://experienceleague.adobe.com/IdmANJYjfwZM29SBj0fDH-BzBet54Zq0VGmIMRRn-hE
product_v2:
  - id: cb954087-f4fc-4456-afb9-e939cabcdc79
    internal-label: Journey Optimizer
feature_v2:
  - id: b49ca41f-eb7a-4f4b-abeb-a97c06fd0c04
    internal-label: Track and monitor
  - id: dc22c819-3f29-4e91-8b7d-5c6719831141
    internal-label: Content management
subfeature_v2:
  - id: fb9a80eb-bebc-492f-a0e9-584595621ebb
    internal-label: Publish
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
level_v2:
  - id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
    internal-label: Beginner
topic_v2:
  - id: bcc5edb5-84c3-4940-9f84-ed88b6c16274
    internal-label: Experimentation
  - id: d095671a-1355-40aa-8b5f-06c33c68080b
    internal-label: Security
  - id: e1e0219c-f879-479f-8427-888ed2a6e9c2
    internal-label: Insights
source-git-commit: 659a4723ac8b7cbaf3ea06c34107bf876612ccb4
workflow-type: tm+mt
source-wordcount: 743
ht-degree: 100%

---

# Bonnes pratiques relatives à Journey Optimizer Experimentation Accelerator {#content-experiment-best-practices}

## Que sont les tests A/B ?

Les tests A/B sont le processus consistant à comparer plusieurs versions d’un élément afin de déterminer laquelle est la plus performante par rapport à un objectif défini.

Les participants et participantes sont affectés de manière aléatoire à une version, connue sous le nom de variante, et leur comportement fait l’objet d’un suivi. Les résultats montrent si une version est statistiquement plus performante que les autres.

## Terminologie clé

| Terme | Définition |
|-|-|
| Commande | Version d’origine utilisée comme référence pour la comparaison. |
| Variante ou traitement | Nouvelle version créée pour un test par rapport à la version d’origine. |
| Hypothèse | Prédiction sur les changements qui produiront des meilleurs résultats, et pourquoi. |
| Taille de l’échantillon | Nombre d’individus ou de sessions inclus dans le test. |
| Signification statistique | Mesure de confiance indiquant que les résultats ne sont pas dus à un hasard. |
| Effet élévateur | Pourcentage d’amélioration ou de baisse d’une variante par rapport à la version d’origine. |
| Mesure principale | Mesure principale utilisée pour déterminer la réussite du test. |
| Mesures secondaires | Mesures complémentaires qui proposent des informations supplémentaires ou permettent de surveiller les effets inattendus. |
| Intervalle de confiance | Plage estimée à l’intérieur de laquelle l’effet réel est susceptible de se produire. |
| Segment | Sous-ensemble spécifique de l’audience analysé indépendamment (par exemple, les nouveaux utilisateurs et nouvelles utilisatrices, les visites mobiles). |

## Bonnes pratiques relatives à l’exécution d’expériences

* **Commencer par une hypothèse claire**

  Une hypothèse solide comprend les changements que vous effectuez, les résultats que vous prévoyez et pourquoi.
Exemple : _nous pensons que la modification de X augmentera Y en raison de Z._

* **Définir une mesure de succès significative**

  Choisissez une mesure qui correspond à vos objectifs généraux. Évitez les mesures de « vanité » qui semblent positives, mais ne reflètent pas l’impact réel.

* **Tester un changement à la fois (si possible)**

  Isoler les variables permet une interprétation précise des résultats. Si vous testez plusieurs changements à la fois, vous ne saurez peut-être pas ce qui a provoqué l’effet.

* **Laisser le test se dérouler suffisamment longtemps**

  Les conclusions prématurées peuvent être trompeuses. Attendez que la taille de l’échantillon soit statistiquement significative avant d’agir.

* **Tenir compte des facteurs externes**

  La saisonnalité, les jours fériés et d’autres changements dans votre environnement peuvent fausser les résultats. Documentez tout ce qui peut influencer le comportement pendant votre test.

* **Utiliser la segmentation judicieusement**

  La répartition des résultats par segment d’audience peut révéler des tendances cachées, mais évitez de surinterpréter les petits échantillons.

* **Documenter et partager les enseignements**

  Conservez une trace claire de ce qui a été testé, pourquoi et ce que vous avez appris. Cela permet de renforcer les connaissances institutionnelles et d’éviter de refaire les mêmes erreurs.

## Mesures courantes

| Mesure | Ce qu’elle mesure | Quand l’utiliser |
|-|-|-|
| Taux de conversion | Pourcentage d’utilisateurs et d’utilisatrices qui effectuent l’action souhaitée. | Utile pour le suivi du succès d’une expérience axée sur des objectifs. |
| Taux de clic (CTR) | Pourcentage d’utilisateurs et d’utilisatrices qui cliquent sur un élément spécifique. | Indique le degré d’efficacité de l’expérience. |
| Taux d’engagement | Niveau d’interaction des utilisateurs et utilisatrices avec l’expérience. | Utile pour mesurer l’intérêt ou l’attention. |
| Taux de rebond | Pourcentage d’utilisateurs et d’utilisatrices qui quittent rapidement sans prendre de mesure. | Peut indiquer une expérience confuse ou inadaptée. |
| Durée de consultation de la page | Temps que les utilisateurs et utilisatrices passent sur une partie spécifique de l’expérience. | Peut refléter le niveau d’intérêt ou de complexité. |
| Chiffre d’affaires par visiteur (RPV) | Chiffre d’affaires moyen généré par utilisateur ou utilisatrice. | Souvent utilisé dans des expériences axées sur le commerce. |
| Taux de rétention | Pourcentage d’utilisateurs et d’utilisatrices qui reviennent ou restent engagés. | Utile pour évaluer la valeur à long terme. |

## Qu’est-ce qui fait une bonne expérience ?

Une bonne expérience ne produit pas seulement un résultat positif, elle apporte aussi un enseignement clair et exploitable.
Voici ce qu’il faut rechercher :

&amp;check; **Fiabilité statistique** : il est peu probable que la différence entre les variantes soit due au hasard.
&amp;check; **Alignement sur les objectifs** : la mesure principale reflète les progrès significatifs accomplis vers un objectif commercial.
&amp;check; **Impact secondaire** : aucun effet secondaire négatif significatif sur les mesures associées.
&amp;check; **Évolutivité** : le résultat peut éclairer les décisions futures ou être généralisé à d’autres domaines.
&amp;check; **Clarté** : la cause du résultat est raisonnablement identifiée et comprise.

L’expérimentation ne consiste pas seulement à trouver la « meilleure » version, mais également à acquérir des connaissances par le biais de tests et d’itérations. Lorsqu’elles sont bien menées, les expériences révèlent des informations qui permettent de prendre des décisions plus intelligentes, d’offrir des expériences utilisateur optimisées et d’obtenir de meilleurs résultats.

>[!BEGINSHADEBOX]

**Exemple :**

* **Entreprise** : chaîne hôtelière.
* **Hypothèse** : si nous utilisons un langage plus urgent sur la page d’accueil, cela entraînera davantage de réservations.
   * **Contrôle** : version d’origine.
   * **Variante** : nouvelle version avec un ton plus urgent.
   * **Mesure principale** : taux de réservation.
   * **Mesures secondaires** : taux de rebond, temps passé sur le site.
* **Résultat** : la variante a entraîné une augmentation de 14 % du taux de réservation, sans impact négatif sur les autres mesures.
* **Action** : envisagez de déployer la variante et d’exécuter des expériences de suivi pour tester des approches similaires dans d’autres domaines.

>[!ENDSHADEBOX]
