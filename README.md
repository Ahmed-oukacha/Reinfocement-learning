# Projets d'Apprentissage par Renforcement


## Table des Matières

<div class="toc">
  <ul>
    <li><a href="#tp01">TP01: Découverte de Gymnasium</a></li>
    <li><a href="#tp02">TP02: Q-Learning</a></li>
    <li><a href="#tp03">TP03: Gestion de Trafic</a></li>
    <li><a href="#tp04">TP04: Taxi-v3 pour les jeux</a></li> 
    <li><a href="#resume">Resume</a></li> 
  </ul>
</div>

<h2 id="tp01">TP01: Découverte de Gymnasium et CartPole</h2>

### Objectifs du TP

Ce TP a pour but d’explorer les bases du **Reinforcement Learning** à travers différentes expériences.

####  Objectifs spécifiques :

1.  **Se familiariser avec les environnements de Reinforcement Learning**  
   - Comprendre les principes de base d’un **agent**, d’un **état**, d’une **action** et d’une **récompense**.

   2. **Explorer l’environnement CartPole-v1**  
   - Tester et analyser le comportement d’un **agent dans OpenAI Gym**.  
   - Observer les dynamiques de l’environnement et la stabilité du pendule inversé.

3. **Implémenter des politiques aléatoires**  
   - Faire agir un agent en sélectionnant des actions **aléatoires**.  
   - Observer et évaluer la performance de cette approche de base.

<h2 id="tp02">TP02: Q-Learning</h2>

#### Objectif du TP
L'objectif de ce TP est de mettre en pratique les concepts fondamentaux de l'**apprentissage par renforcement** à travers l’algorithme **Q-Learning**.

####  Contenu du TP
Au fil d’exercices progressifs, les étudiants vont :

1.  **Implémenter l’algorithme Q-Learning**
   - Comprendre les étapes de mise à jour de la **Q-Table**.

2. **Analyser les stratégies d'exploration et d'exploitation**
   - Observer l’impact du **taux d’exploration (ε)** et de l'**exploitation** sur l’apprentissage.

3.  **Étudier la convergence des valeurs Q**
   - Visualiser comment les valeurs Q évoluent et convergent vers une **politique optimale**.

####  Environnement d'expérimentation
L’environnement **FrozenLake** de **OpenAI Gym** sera utilisé comme terrain d’expérimentation.  
Il permettra d'illustrer concrètement **comment un agent apprend à optimiser ses décisions** en fonction des mises à jour successives de sa **Q-Table**.

<h2 id="tp03">TP03: Gestion de Trafic</h2>
#### Objectif du TP  
Ce travail pratique vise à explorer **l’optimisation des feux de circulation** à l’aide de l’**apprentissage par renforcement**.

####  Les Étapes du TP  
1.  **Découverte de l’environnement**  
   - Simuler un **réseau routier** et analyser le **flux de trafic**.
  
2. **Implémentation des algorithmes**  
   - Appliquer **Q-Learning** et **SARSA** pour apprendre une politique optimale.  

3.  **Analyse et Comparaison**  
   - Comparer les performances des algorithmes à l’aide de **graphiques** et d’**évaluations quantitatives**.  

**Objectif final :** Trouver une stratégie efficace pour **minimiser les embouteillages** et améliorer la **fluidité du trafic** !  
<h2 id="tp04">TP04: Taxi-v3 pour les jeux</h2>
### Objectif du TP  
L'objectif de ce TP est de **familiariser les étudiants** avec l’implémentation de l’algorithme **Proximal Policy Optimization (PPO)**, une méthode d’apprentissage par renforcement basée sur des politiques.

#### Contenu du TP  
1. **Initialisation de l'environement et des structures des donnes**  

2.  **Exploration et collecte d'episode**  

3. **Mise a jour de La politique avec PPO**

4. **Evaluation de l'agent apres l'entrainement**

<h2 id="resume">Resume</h2>
En résumé, ces TP ont fourni une solide compréhension des concepts de l'apprentissage par renforcement, depuis les politiques simples basées sur des actions aléatoires, 
jusqu'aux méthodes avancées de mise à jour de politique, comme le PPO. Ces compétences sont essentielles pour aborder des problématiques réelles en IA, comme la gestion
de trafic ou les jeux complexes, tout en fournissant une base solide pour explorer des approches plus avancées dans le domaine.
