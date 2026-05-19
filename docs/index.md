---
title: Vue d'ensemble du projet
---

<style>
    @media screen and (min-width: 76em) {
        .md-sidebar--primary {
            display: none !important;
        }
    }
</style>

# Vue d'ensemble du projet

!!! info "Informations générales"
    **Session**: Été 2026  
    **Auteur(s)**: Setayesh Abbasi Moghadam  
    **Thème(s)**: HCI, optimisation de prompts, visualisation de l'incertitude  
    **Superviseur(s)**: Ian Arawjo 
    **Collaborateur(s):** Cassandre Hamel 

## Description du projet

### Contexte

> L'ingénierie des prompts est une pratique centrale dans le développement de systèmes basés sur les grands modèles de langage (LLM). Les développeurs rédigent et affinent des instructions soumises aux LLMs afin d'obtenir des comportements précis. Cependant, ce processus reste coûteux, non systématique et difficile à reproduire, en particulier pour les développeurs indépendants et les petites organisations pour qui le coût computationnel représente un obstacle majeur à l'adoption de l'IA.


### Problématique

> En l'absence de méthodes rigoureuses, les développeurs ont recours à des essais-erreurs non structurés, explorant un espace de configurations trop vaste pour être parcouru exhaustivement. Des outils d'optimisation automatique de prompts (APO) ont été proposés, mais ils ne quantifient pas l'incertitude associée à leurs résultats et n'offrent aucun contrôle à l'utilisateur pendant le processus d'optimisation. Il manque donc des outils interactifs qui permettent à l'utilisateur de guider l'optimisation en temps réel tout en comprenant l'incertitude des résultats.

### Proposition et objectifs

> Ce projet étudie comment des fonctionnalités interactives — notamment la visualisation de l'incertitude et le pilotage en cours d'optimisation — intégrées à l'outil **PromptCEO** influencent le comportement des développeurs, leur charge cognitive, et la qualité des prompts obtenus dans un budget computationnel fixe.

> Les deux objectifs principaux sont :

> 1. Évaluer si la **visualisation de l'incertitude** de PromptCEO amène les utilisateurs à trouver des prompts de meilleure qualité dans un budget fixe, comparativement à l'exploration manuelle et à une APO non interactive.
> 2. Évaluer si le **pilotage interactif** de PromptCEO amène les utilisateurs à trouver des prompts de meilleure qualité dans un budget fixe, comparativement à l'exploration manuelle et à une APO non interactive.


### Méthodologie

> L'étude combine le développement du système PromptCEO et des études d'utilisabilité auprès de participants ayant une expérience avec les LLMs (développeurs, chercheurs en apprentissage automatique, auditeurs en IA). Les participants seront soumis à 3 tâches d'optimisation de prompts dans 3 conditions expérimentales différentes. Chaque session durera au maximum 90 minutes et sera suivie d'un questionnaire SUS et d'une entrevue semi-structurée. Des tests d'utilisabilité « guérilla » (30 minutes) seront également menés en amont pour raffiner l'interface de manière formative.


### Validation et Évaluation

> La qualité des prompts trouvés sera mesurée quantitativement selon un budget computationnel fixe. Les résultats seront comparés entre les 3 conditions (PromptCEO interactif, APO non interactive, exploration manuelle). Des indicateurs qualitatifs seront recueillis via le questionnaire SUS et les entrevues post-étude. L'étude vise un échantillon de 24 à 36 participants pour atteindre une puissance statistique suffisante, avec 16 participants supplémentaires pour les tests formatifs.


## Équipe

| Membre                      | Rôle                                                                 |
|-----------------------------|----------------------------------------------------------------------|
| **Ian Arawjo**              | Superviseur principal, Professeur adjoint au DIRO, UdeM              |
| **Eugene Syriani**          | Co-directeur, Professeur titulaire au DIRO, UdeM                     |
| **Cassandre Hamel**         | Collaboratrice principale, étudiante M.Sc. en informatique, DIRO/Mila|
| **Setayesh Abbasi Moghadam**| Étudiante (travail dirigé), Baccalauréat en informatique, DIRO       |


## Échéancier

!!! info
    Le suivi complet est disponible dans la page [Suivi de projet](suivi.md).

| Activités                      | Début   |   Fin   | Livrable                            | Statut      |
|--------------------------------|---------|---------|-------------------------------------|-------------|
| Ouverture de projet            | 4 mai   | 15 mai  | Proposition de projet               | ✅ Terminé  |
| Études préliminaires           | 4 mai   | 22 mai  | Document d'analyse                  | 🔄 En cours |
| Présentation + Rapport         | 7 aout  | 14 aout | Présentation + Rapport              | ⏳ À venir  |
