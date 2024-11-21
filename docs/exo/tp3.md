# TP 3 : Conception d’un Système Dynamique - La Grue Rotative

## Introduction

Dans ce TP, vous allez concevoir une grue rotative capable de déplacer un objet le long de son bras horizontal, tout en prenant en compte les forces dynamiques générées par la rotation. Ce projet vous permettra de maîtriser les concepts liés aux systèmes en rotation, notamment la force centrifuge et les frottements, et de concevoir un mécanisme fonctionnel pour déplacer une charge.

![](https://loadmate.in/wp-content/uploads/2021/04/Pillar-Mounted-Jib-Crane-Chain-Hoist-1.jpeg)

---

## Étape 1 : Analyse dynamique

Lors de la rotation de la grue, l’objet transporté est soumis à plusieurs forces. Réalisée le bilan des actions mécanique pour comprendre et modéliser la dynamique de l'objet en mouvement.
Vous prendrez en compte, l'effet de la force centrifuge ainsi que les frottements statiques et dynamique.

### Calculs initiaux

Pour une charge de $500 kg$ située à une distance de $6 m$ de l’axe de rotation, avec une vitesse angulaire de $0,1 rad.s^{-1}$, calculez les forces suivantes :

- La force centrifuge.
- Les forces de frottement statique et dynamique.

Notez vos résultats dans un tableur pour automatiser les ajustements si des paramètres évoluent.

Déterminez l'acceleration maximum pour minimiser le temps d'accélération du système jusqu'à une vitesse de $3m.s^{-1}$

## Étape 2 : Dimensionnement du mécanisme de déplacement

### Objectif

Vous devez concevoir un mécanisme permettant de déplacer la charge sur l’axe horizontal. Ce mécanisme devra :

- Générer une force suffisante pour surmonter les frottements et la force centrifuge.
- Être compact et simple à fabriquer.

### Approche

Basez votre conception sur une solution mécanique simple, comme :

- **Un moteur linéaire** pour tracter la charge.
- **Un système de poulies et câbles** pour transmettre la force.
- **Un rail et un chariot guidé** pour assurer le déplacement.

Précisez dans vos calculs la force minimale requise pour déplacer l’objet, ainsi que les dimensions critiques du mécanisme (longueur des câbles, diamètre des poulies, etc.).

---

## Étape 3 : Conception 3D simplifiée

Pour simplifier le travail de modélisation, limitez-vous aux éléments essentiels :

1. **Le bras horizontal** : Modélisez une poutre simple de section carrée ou rectangulaire.
2. **La charge transportée** : Représentez-la par un simple bloc de masse.
3. **Le mécanisme de déplacement** : Modélisez uniquement les éléments critiques, comme le câble ou le rail, en précisant leurs positions et dimensions.

Assemblez ces éléments dans **3DExperience** pour vérifier leur intégration.

---

## Livrables

À la fin de ce TP, vous devez fournir :

1. Les calculs détaillés des forces et dimensions dans un rapport clair.
2. Le modèle 3D simplifié, intégrant le bras, la charge et le mécanisme.
3. Un tableau Excel montrant les ajustements de vos calculs.

---

**Bon courage !** Ce projet mettra en lumière vos compétences en dynamique et en conception mécanique tout en vous initiant à la simulation des systèmes dynamiques.
