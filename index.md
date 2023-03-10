---
marp: true
style: |
  .grid {
    display: grid;
  }

  .grid-cols-2 {
    grid-template-columns: repeat(2,minmax(0,1fr));
  }

  .grid-cols-3 {
    grid-template-columns: repeat(3,minmax(0,1fr));
  }

  .gap-4 {
    gap: 1rem;
  }
---

# Introduction à Scrum

Fabian Vilers

[@fvilers](https://github.com/fvilers)
[http://www.linkedin.com/in/fvilers](http://www.linkedin.com/in/fvilers)

---

# Qu'est-ce que Scrum?

- Scrum est un processus agile qui permet de produire la plus grande valeur métier dans la durée la plus courte
- Du logiciel qui fonctionne est produit à chaque Sprint
- Le business définit les priorités. L'équipe s'organise elle-même pour déterminer la meilleure façon de produire les exigences les plus prioritaires
- A chaque fin de Sprint, tout le monde peut voir fonctionner le produit courant et décider soit de le livrer dans l'état, soit de continuer à l'améliorer pendant un Sprint supplémentaire

---

# Caractéristiques de Scrum

- Équipe responsable, en auto-organisation
- Avancement du produit par une série de Sprints d'un mois ou moins
- Exigences définies comme des éléments d'une liste appelée Product Backlog
- Pas de prescription de pratiques d'ingénierie
- Utilisation de règles génériques permettant de créer un environnement agile pour un projet
- Scrum est l'un des processus agiles parmi d'autre

---

# Le Manifeste Agile

<div class="grid grid-cols-2 gap-4">
<div>

## Valeurs

- Personnes et interactions
- Logiciel qui fonctionne
- Collaboration avec le client
- Adaptation au changement

</div>
<div>

## Plutôt que

- Processus et outils
- Documentation
- Négociation à partir d'un contrat
- Suivi d'un plan

</div>
</div>

---

# Sprints

- Les projets Scrum progressent par une série de Sprints
- La durée d'un Sprint est de 2 à 4 semaines
- Une durée constante apporte un meilleur rythme
- Le produit (partiel) est conçu, codé et testé pendant le sprint

---

# Le cadre de Scrum

<div class="grid grid-cols-3 gap-4">
<div>

## Rôles

- Product Owner
- Scrum Master
- L'équipe

</div>
<div>

## Cérémonials

- Sprint Planning
- Sprint Review
- Sprint Retrospective
- Daily Scrum Meeting

</div>

<div>

## Artefacts

- Product Backlog
- Sprint Backlog
- Burndown Chart

</div>
</div>

---

# Les rôles

---

# Le Product Owner

- Définit les fonctionnalités du produit
- Choisit la date et le contenu de la release
- Responsable du retour sur investissement
- Définit les priorités dans le Backlog en fonction de la valeur métier
- Ajuste les fonctionnalités et les priorités à chaque sprint si nécessaire
- Accepte ou rejette les résultats

---

# Le Scrum Master

- Représente le management du projet
- Responsable de l'application par l'équipe les valeurs et les pratiques de Scrum
- Élimine les obstacles
- S'assure que l'équipe est complètement fonctionnelle et productive
- Facilite une coopération poussée entre tous les rôles et fonctions
- Protège l'équipe des interférences extérieures

---

# L'équipe

- De 5 à 9 personnes, avec une composition stable durant un Sprint
- Regroupant tous les rôles
- Développeurs, testeurs, spécialiste IHM, etc.
- De préférence à plein temps sur le projet (exceptions possibles)
- L'équipe s'organise par elle-même
- Idéalement, pas de titres

---

# Les cérémonials

---

# Le Sprint Planning

- L'équipe choisit, à partir du Product Backlog, les éléments qu'elle s'engage à finir
- La liste des tâches est créée
- Les tâches sont identifiées et estimées (1-16 heures)
- Collectivement, pas seulement par le Scrum Master
- La conception de haut niveau est abordée

---

# Le Daily Scrum

<div class="grid grid-cols-2 gap-4">
<div>

## Paramètres

- Tous les jours, 15 minutes, debout
- Pas fait pour résoudre les problèmes
- Tout le monde est invité mais seuls les membres de l'équipe peuvent parler
- Permet d'éviter l'organisation d'autres réunions

</div>
<div>

## Chacun répond à 3 questions

- Qu'ai-je fait hier ?
- Que vais-je faire aujourd'hui ?
- Y a-t-il un obstacle qui me freine ?
- Il ne s'agit pas d'un compte-rendus au Scrum Master mais d'un engagement devant ses pairs

</div>
</div>

---

# Le Sprint Review

- L'équipe présente ce qu'elle a réalisé pendant le Sprint
- Se fait avec une démo des nouvelles fonctionnalités ou de l'architecture
- Informel, préparation en moins de 2h
- Pas de slides
- Toute l'équipe participe
- On invite du monde

---

# Le Sprint Retrospective

<div class="grid-cols-2">
<div>

- Réfléchir régulièrement à ce qui marche et ce qui ne marche pas
- Dure en général de 15 à 30 minutes
- Organisé à la fin de chaque Sprint
- Toute l'équipe participe (Scrum Master, Product Owner, et l'équipe de réalisation)
- Éventuellement avec des clients et autres intervenants

</div>
<div>

- Toute l'équipe collecte du feedback et discute sur ce qu'elle aimerait :
  - commencer à faire
  - arrêter de faire
  - continuer de faire

</div>
</div>

---

# Les artefacts

---

# Le Product Backlog

- Représente les exigences
- Une liste de tout ce qui va entraîner du travail pour l'équipe
- Exprimé de telle façon que chaque élément apporte de la valeur aux utilisateurs ou clients du produit
- Les priorités sont définies par le Product Owner
- Les priorités sont revues à chaque sprint

---

# Le Sprint Goal

- Un bref énoncé de sur quoi va porter l'essentiel du travail pendant le Sprint

---

# La gestion du Sprint Backlog

- Chacun s'engage sur du travail qu'il choisit
- Le travail n'est jamais attribué par un autre
- L'estimation du reste à faire est ajustée tous les jours
- N'importe qui peut ajouter, supprimer ou changer la liste des tâches
- Le travail du sprint émerge progressivement
- Si un travail n'est pas clair, il faut définir une tâche avec plus de temps et la décomposer ensuite
- Mise à jour du travail restant quand il est mieux connu

---

# Le Sprint Burndown chart

!["Le Sprint Burndown chart](1920px-SampleBurndownChart.svg.png)

---

# Liste de lecture

- "Agile Estimating and Planning", "Succeeding with Agile", et "User Stories Applied for Agile Software - Development" de Mike Cohn
- "Agile Project Management with Scrum", et "Scrum and The Enterprise" de Ken Schwaber
- "Scrum - Le guide pratique de la méthode agile la plus populaire" par Claude Aubry

---

# Source

- Scrum Presentation, by [Mountain Goat Software](http://www.mountaingoatsoftware.com/), licensed under CC BY 3.0
