---
solution: Journey Optimizer
product: journey optimizer
title: Experimentation Accelerator de Journey Optimizer
description: Utilisation des données dans l’IA avec Journey Optimizer Experimentation Accelerator
topic: Content Management
role: User
level: Beginner
keywords: contenu, expérience, multiple, audience, traitement
TQID: https://experienceleague.adobe.com/FaQ5-cPzhnIplEoL1HwVh390jot-EA8G5u6JP8CVneI
product_v2: id: cb954087-f4fc-4456-afb9-e939cabcdc79
feature_v2: id: b3538224-471e-4c63-a444-9b19d89ae29cid: b49ca41f-eb7a-4f4b-abeb-a97c06fd0c04id: dc22c819-3f29-4e91-8b7d-5c6719831141
subfeature_v2: id: fb9a80eb-bebc-492f-a0e9-584595621ebb
role_v2: id: b69b2659-1057-424e-8fc5-ed9e016dc554
level_v2: id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
topic_v2: id: a004cc84-67b9-4a33-a3a7-8ec7273ef4dcid: b5ce8718-c3af-4fdb-a1a9-fca32f83a87cid: bcc5edb5-84c3-4940-9f84-ed88b6c16274id: d095671a-1355-40aa-8b5f-06c33c68080bid: e1e0219c-f879-479f-8427-888ed2a6e9c2id: eb30f47f-d87a-400f-8f78-63ce7979ff56
source-git-commit: 659a4723ac8b7cbaf3ea06c34107bf876612ccb4
workflow-type: tm+mt
source-wordcount: 441
ht-degree: 100%

---

# Utilisation des données dans l’IA avec Journey Optimizer Experimentation Accelerator{#experiment-accelerator-security}

**Adobe Journey Optimizer Experimentation Accelerator** vous permet de découvrir automatiquement des informations et de proposer des opportunités pour améliorer vos expériences et votre programme d’expérimentation. La solution tire parti de l’IA et du machine learning pour fournir ces recommandations. Cette section explique la façon dont les données de vos clientes et clients sont utilisées dans **Journey Optimizer Experimentation Accelerator**.

## Quelles données Journey Optimizer Experimentation Accelerator utilise-t-il ?

Actuellement, **Journey Optimizer Experimentation Accelerator** utilise trois types de données :

* **Métadonnées de l’expérience** : nom de l’expérience, définition de l’audience utilisée dans l’expérience et traitements dans l’expérience, par exemple le nom, les pourcentages de partage, l’emplacement ou la surface sur laquelle l’expérience est diffusée.

* **Performances des traitements** : nombre de personnes, moyenne de la mesure de succès et écart type pour chaque traitement.

* **Contenu du traitement** : HTML rendu et copie d’écran du traitement telle qu’il apparaîtrait à un utilisateur ou une utilisatrice sur votre site web.

## Que fait Journey Optimizer Experimentation Accelerator avec ces données ?

**Journey Optimizer Experimentation Accelerator** prend le contenu de chaque traitement et crée une incorporation, c’est-à-dire une représentation mathématique du contenu, puis met en corrélation ces incorporations avec les performances des traitements. Ce processus permet d’extraire les attributs de contenu qui se sont révélés les plus performants en vue d’une utilisation future. Ces attributs sont ensuite intégrés dans un grand modèle de langage hébergé par Adobe, qui les convertit en instructions lisibles par les utilisateurs et les utilisatrices, utilisées pour générer des informations et suggérer des opportunités.

## Quelles restrictions Journey Optimizer Experimentation Accelerator applique-t-il aux données utilisées ?

Chaque personne cliente est affectée à une organisation et à un sandbox spécifiques. Un modèle dédié est entraîné pour chaque sandbox. Lorsqu’un sandbox est supprimé, l’ensemble des données, des signaux et des modèles associés sont définitivement supprimés.

* Nous utilisons uniquement les données client pour entraîner ou affiner le modèle de ce client ou cette cliente.

* Nous ne mélangeons jamais les clients et clientes pour entraîner ou affiner un modèle.

## Les modèles ou l’IA d’Adobe modifient-ils automatiquement l’expérience utilisateur d’une marque ?

Non. **Journey Optimizer Experimentation Accelerator** ne fait que des recommandations sur ce qui peut être modifié et sur la façon de le faire. Seuls les personnes autorisées à modifier l’expérience à l’aide de Journey Optimizer ou de Target peuvent appliquer ces recommandations. Toutes les recommandations peuvent être vérifiées et modifiées avant d’être publiées.

## Existe-t-il un risque pour les données ou la stabilité du système ?

**Journey Optimizer Experimentation Accelerator** ingère et analyse uniquement les données, produisant des informations et des recommandations pour les tests futurs. Il ne dispose pas de l’accès nécessaire pour modifier les paramètres de test. Toutes les suggestions générées dans l’outil sont envoyées à Target et à Journey Optimizer pour être mises en œuvre, ce qui n’a aucun impact sur les activités en cours des clients et clientes.
