# Conception d'un bras robotisé de type SCARA avec IGUS

## 1. Contexte et objectifs

![alt text](https://cdn.globalso.com/scic-robot/industrial-robot-2442.jpg){.img-small align=right}

Dans le cadre du cours de Construction Mécanique, vous êtes sollicités pour concevoir et dimensionner un bras robotisé de type SCARA (Selective Compliance Assembly Robot Arm). Par chance, ce projet se déroule en même temps qu'une intervention de la société **IGUS**, fournisseur de composants mécaniques (paliers, guides linéaires, passe-câbles, etc.). 

L’objectif principal est de **concevoir** puis de **valider** la faisabilité mécanique d’un robot SCARA destiné à la manipulation d’objets de petite taille (quelques centaines de grammes à 1 kg maximum). 

À l’issue de ce projet, vous devrez être capables de :

1. Recenser et structurer l’ensemble des composants du robot selon la méthode **Product Breakdown Structure (PBS)**.
2. Réaliser le **schéma cinématique** en identifiant les liaisons mécaniques.
3. Modéliser en **CAO** (sous 3DExperience) les éléments principaux du robot (On ignorera, les vis, les éléments électrique, les joints..).
4. Simuler et valider la **résistance mécanique** d’une des pièces principales par **analyse par éléments finis** (FEA).

---

## 2. Organisation générale des séances

Le projet est découpé en **trois** séances principales :

1. **TP1 : Brainstorming et définition des composants (avec IGUS)**  
   - Présentation du sujet et du contexte.  
   - Visite du stand IGUS pour découvrir la gamme de composants disponibles (paliers, coussinets, passe-câbles, etc.).  
   - Brainstorming par équipe de 4 pour identifier les principaux éléments du robot et amorcer la **Product Breakdown Structure**.

2. **TP2 : Schéma cinématique et réalisation de la CAO**  
   - Validation du schéma cinématique et définition des **liaisons** mécaniques (rotule, pivot, glissière…).  
   - Modélisation de l’architecture du robot SCARA sous **3DExperience** (placement des axes, bras, supports, motorisations, etc.).  
   - Début de la préparation des pièces en vue de la simulation.

3. **TP3 : Simulation, validation et rapport**  
   - Mise en place de l’étude **par éléments finis** sur la ou les pièces critiques.  
   - Analyse des résultats, validation des choix et proposition d’améliorations.  
   - Rédaction du **rapport final** détaillant la démarche et les conclusions.

---

## 3. Contenu du projet et livrables

### 3.1 Product Breakdown Structure (PBS)
- Identifier de manière hiérarchique tous les composants du bras SCARA :  
  1. **Structure principale** (colonnes, bras, embase, etc.)  
  2. **Systèmes de transmission** (moteurs, réducteurs, courroies, pignons, etc.)  
  3. **Guidages et liaisons** (paliers, roulements, coussinets IGUS, axes…)  
  4. **Systèmes d’alimentation et de câblage** (câbles, passe-câbles, connecteurs, etc.)  
  5. **Systèmes de contrôle** (capteurs de position, API/cartes de contrôle moteurs, etc.)  

- Cette structure doit être suffisamment détaillée pour couvrir **tous** les éléments du robot : du plus grand ensemble (l’axe rotatif principal) aux plus petites pièces (vis, bagues, etc.).

### 3.2 Schéma cinématique et identification des liaisons
- Représenter **schématiquement** les différents sous-ensembles et axes de rotation/translation.  
- Identifier précisément les types de **liaisons mécaniques** (pivot, glissière, encastrement…) au sein du mécanisme (par exemple : liaison pivot entre le bras 1 et le bras 2, liaison pivot entre le bras et le socle, etc.).  
- Numéroter et nommer clairement les liaisons pour les référencer dans le rapport.

### 3.3 Maquette numérique (3DExperience)
- Modéliser la **géométrie 3D** des éléments mécaniques principaux du robot SCARA.  
- Respecter les **contraintes d’encombrement** et de positionnement des axes.  
- Intégrer les pièces sélectionnées chez IGUS (paliers, coussinets…) selon les dimensions réelles.  
- Organiser la maquette de manière claire (nomenclature, assemblage, structure d’arborescence).

### 3.4 Simulation mécanique (Analyse par éléments finis)
- Choisir **une pièce critique** du robot (par exemple, un bras ou un support de palier) et justifier son choix (pièce soumise à forte contrainte, poids, ou autre).  
- Définir les **conditions aux limites** (appuis, chargements, couples, efforts, etc.).  
- Effectuer la **simulation par éléments finis** sous 3DExperience (ou tout autre module compatible).  
- Présenter et interpréter les **résultats** (contraintes, déformations, facteurs de sécurité).  
- Conclure sur la **validité** de la pièce et proposer d’éventuelles **optimisations** (allègement, choix d’un autre matériau, renforcement local).

### 3.5 Rapport final
- Le rapport devra intégrer :  
  1. **Product Breakdown Structure**
  2. **Schéma cinématique** avec identification des liaisons  
  3. **Captures d’écran** de la maquette 3D sous 3DExperience  
  4. **Méthodologie de simulation** et **résultats** d’analyse par éléments finis  
  5. **Conclusion** sur la conception et propositions d’amélioration  
  6. **Annexes** (plans 2D, nomenclature, etc.)

---

## 4. Contraintes et dimensions de référence

1. **Charge utile maximale** : ~1 kg  
2. **Encombrement** : bras d’environ 300mm de portée (longueur entre l’axe vertical et l’extrémité du bras)  
3. **Vitesse de rotation** : vitesse angulaire d’environ 60 °/s (à adapter selon la motorisation)  
4. **Alimentation électrique** : 24 V ou 48 V DC (selon la gamme de moteurs envisagée)  
5. **Matériaux** : privilégier des pièces légères (aluminium, plastiques techniques ou composites) pour les bras ; pièces structurelles possibles en acier ou alliage léger.  
6. **Composants IGUS** : utiliser au moins un palier, un coussinet et un passe-câble provenant des gammes IGUS, justifier.

---

## 5. Planning détaillé

- **TP1 (3 h)** :  
  1. Présentation du sujet, visite du stand IGUS, découverte des composants.  
  2. Brainstorming en équipe : premiers choix techniques, pré-PBS.

- **TP2 (3 h)** :  
  1. Finalisation du **schéma cinématique**, identification des liaisons.  
  2. Conception **CAO** sous 3DExperience (armature générale et insertion des composants).

- **TP3 (3 h)** :  
  1. **Simulation** par éléments finis (sélection de la pièce, conditions aux limites, résultats).  
  2. Analyse, validation et **conclusion** (rédaction du rapport final).

---

## 7. Critères d’évaluation

1. **Qualité du Product Breakdown Structure** (exhaustivité et organisation).  
2. **Pertinence du schéma cinématique** et bonne identification des liaisons.  
3. **Qualité de la maquette CAO** (bonne organisation, nomenclature, respect des dimensions).  
4. **Rigueur de la simulation** (définition des conditions limites, interprétation des résultats).  
5. **Qualité du rapport** (organisation, clarté, justifications techniques, illustrations).  
6. **Respect du planning** (rendus en temps et en heure).

---

## 8. Conclusion

Ce projet vous permettra de mettre en pratique l’ensemble des compétences vues en Construction Mécanique :  

- Méthodologie de conception (PBS, schéma cinématique, choix des composants),  
- Utilisation d’un logiciel de CAO (3DExperience) et d’analyse par éléments finis,  
- Esprit d’équipe et gestion de projet,  
- Justification technique et rédaction d’un rapport d’ingénierie.

Le partenariat avec **IGUS** vous donne accès à une **gamme complète** de composants fiables et innovants pour vos besoins de guidage et de liaisons. Profitez de cette opportunité pour concevoir un bras robotisé **performant** et **facile à maintenir**.

---

> **NB** : En plus de ce cahier des charges, n’hésitez pas à consulter la documentation technique IGUS et à vous rapprocher de leurs experts pour mieux comprendre les contraintes et les applications réelles de leurs produits.