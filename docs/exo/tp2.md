# TP 2 : Conception et dimensionnement d'une Balance romaine

![](https://www.lecompendium.com/dossier_meca_02_romaines_et_pesons_a_contrepoids/romaines_b06_le_compendium.gif){.center}

## Objectif

Vous allez concevoir une balance capable de mesurer avec précision des poids de **0 à 30 kg**, avec une graduation définie (par exemple, 1 kg). La balance sera composée d’un **bras** possèdant une graduation d'un côté et un **contrepoids** de l'autre. Ce TP vous permettra d’appliquer les principes de l’équilibre statique et d’explorer la modélisation 3D sur **3DExperience**.

---

## Contexte
La balance devra être conçue pour :

- Avoir une lecture précise grâce à une graduation définie.
- Maintenir un équilibre stable pour toute la plage de poids.
- Respecter les contraintes physiques imposées, notamment l’encombrement du contrepoids.

Vous utiliserez 3DExperience pour modéliser la balance et valider vos calculs.

---

## Étape 1 : Calculs Préliminaires

### Analyse de l'équilibre statique

Nous commencerons par définir les dimensions du bras. puis donner la longueur totale du bras de la balance.
Le bras gradué de la balance sera constitué d'une tige en acier de **diamètre 15mm**.

!!! question "Question 1"
    - Déterminez la longueur optimale du bras pour assurer une lecture précise du poids à haque graduation (par exemple, 1 kg tous les 20mm).
    - Calculez le poids total du bras gradué

### Dimensions et matériau du contrepoids

!!! question "Question 2"
    En utilisant le principe fondamental de la statique, calculez le poids idéal du contrepoids permettant d'assurer l'équilibre.

Choisissez un matériaux parmis ceux disponibles :

  - Acier (\(7,86 \, \text{g/cm}^3\)).
  - Aluminium (\(2.7 \, \text{g/cm}^3\)).
  - Plomb (\(11.3 \, \text{g/cm}^3\)).

---

## Étape 2 : Planification de la Conception

### Configuration de la balance et du contrepoids

La méthode de fonderie disponible impose un volume maximum pour la conception du contrepoids. Il doit respecter une contrainte d’encombrement maximale de \(20 \times 20 \times 10 \, \text{cm}\). 

Planifiez la configuration de la balance, en tenant compte des éléments suivants :

- Position du pivot : Localisez le point d’appui du bras pour assurer un fonctionnement optimal.
- Placement du contrepoids : Assurez-vous que sa position équilibre le système tout en respectant l’encombrement.
- Système de mesure : Déterminez la façon dont les poids seront mesurés avec précision sur la balance.
- Forme du contrepoids En fonction du matériaux choisi, concevez un contrepoids qui respecte l'encombrement imposé. 

!!! question "Question 3"
    Réalisez un schéma de synthèse de vos décisions de conceptions.

---

## Étape 3 : Modélisation sur 3DExperience

### Création du bras

1. Lancez l’application **Assembly Design** et créez un nouvel assemblage.
2. Dans cet assemblage, ajoutez une nouvelle pièce pour le bras.
3. Modélisez le bras avec la longueur calculée

### Conception du contrepoids

1. Ajoutez une nouvelle pièce dans l’assemblage pour représenter le contrepoids.
2. Modélisez la forme du contrepoids en respectant les dimensions maximales imposées. 
3. Ajustez sa position pour garantir l’équilibre statique.

### Conception du bâti

1. Ajoutez une nouvelle pièce dans l’assemblage pour représenter le bâti.
2. Créer un bâti possèdant un pivot, et une interface pour le bras gradué et le contrepoids 

### Validation de l'équilibre

1. Vérifier la position des éléments et l'équilibre statique

---

## Étape 4 : Livrables

À la fin de ce TP, vous devez fournir :

1. Le modèle 3D complet de la balance dans 3DExperience.
2. Les calculs justifiant :
   - La longueur du bras.
   - Le choix du matériau et les dimensions du contrepoids.
   - Un schéma dimensionné de votre conception
3. Un rapport expliquant comment votre conception respecte les contraintes et les objectifs définis.

---

**Bon courage !** Appliquez vos connaissances en mécanique et en modélisation pour relever ce défi.
