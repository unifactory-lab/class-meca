# TP RDM sur 3DExperience : Simulation d'une poutre IPN en acier galvanisé

## Objectif
Dans ce TP, les étudiants apprendront à modéliser une poutre IPN de 2,8 m, à attribuer un matériau avec les propriétés de l'acier galvanisé, et à effectuer une analyse statique simple via l'application Static Study de 3DExperience. L'analyse portera sur la distribution de contraintes, notamment selon le critère de Von Mises.

## Étapes du TP
### 1. Modélisation de la poutre IPN avec Part Design

1. Ouvrir l'application **Part Design**.
2. Créer un nouveau document pour la poutre.
3. Dessiner le profil de la poutre IPN en se basant sur le schéma de cotation fourni. Les dimensions sont disponibles dans le fichier PDF suivant :  
   
[Télécharger le schéma de cotation](./images/tp.rdm/dim.pdf){.md-button}

4. Extruder le profil sur une longueur de 2,8 m afin d'obtenir la poutre.

### 2. Création et application d’un matériau de simulation (Acier galvanisé)

1. Passer à l'application **Assembly Design**.
2. Créer un nouveau matériau :

   - Naviguer dans le menu pour trouver l'option de création d'un **nouveau matériau**.
   - Ouvrir le panneau d'édition pour définir les propriétés du matériau. (Voir les captures d'écran correspondantes pour guider l'opération) :
     - ![Édition du matériau](./images/tp.rdm/add.material.edit.dev.PNG)
     - ![Édition du matériau](./images/tp.rdm/add.material.edit.PNG)
     - ![Ajout du matériau](./images/tp.rdm/add.material.PNG)
     - ![Propriétés du matériau](./images/tp.rdm/add.material.properties.PNG)
     - 
3. Rechercher sur Internet les propriétés mécaniques de l'acier galvanisé (module d'élasticité, coefficient de Poisson, densité, limite d'élasticité, etc.).
4. Saisir les propriétés trouvées dans les champs correspondants.
5. Sauvegarder le matériau créé.
6. Appliquer ce matériau à la poutre :

   - Sélectionner la poutre dans l'arborescence.
   - Utiliser l'option pour définir le matériau de la pièce. (Voir la capture d'écran)
     - ![Définir le matériau sur la poutre](./images/tp.rdm/set.material.PNG)

### 3. Préparation de l’étude statique avec Static Study

1. Ouvrir l'application **Static Study**.

![Application Static Study](./images/tp.rdm/app.static.PNG)

1. Utiliser l'assistant de simulation pour guider les étapes :

![Organisation du projet](./images/tp.rdm/orga.PNG)

![Assistant de simulation](./images/tp.rdm/app.static.PNG)

3. Suivre les instructions de l'assistant pour configurer la simulation.

### 4. Application des conditions aux limites et chargement
#### 1. Encastrement :

- Sélectionner une des extrémités de la poutre.
- Appliquer un encastrement pour fixer cette extrémité.

![Condition d'encastrement](./images/tp.rdm/displacement.fix.PNG)

#### 2. Déplacement imposé :

À l'autre extrémité de la poutre, imposer un déplacement de 1 mm.

![Déplacement imposé](./images/tp.rdm/displacement.PNG)

#### 3. Maillage et simulation

1. Mailler la géométrie :

   - Ajuster la taille des éléments si nécessaire pour une bonne résolution.
  
2. Lancer la simulation statique.
3. Une fois la simulation terminée, afficher les résultats :

4. Visualiser le critère de Von Mises pour observer la distribution des contraintes dans la poutre.

![Résultats Von Mises](./images/tp.rdm/vm.PNG)


## Conclusion
À la fin de ce TP, les étudiants auront acquis les compétences pour :
- Modéliser une poutre en utilisant Part Design.
- Créer et attribuer un matériau personnalisé dans Assembly Design.
- Préparer et exécuter une analyse statique avec des conditions aux limites et des chargements appliqués.
- Interpréter les résultats d'une simulation en utilisant le critère de Von Mises pour évaluer les contraintes dans une structure.

