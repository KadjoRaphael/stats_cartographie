---
title: TD2 - Relation quanti-quanti
nav_order: 4
---

# TD2 - Relation entre deux variables quantitatives

**Thème :** santé et espérance de vie dans les pays du monde - introduction
à l'analyse de la relation entre deux variables quantitatives.

Dans le TD1, nous avons appris à **décrire une variable à la fois**.

Dans ce deuxième TD, nous allons franchir une nouvelle étape : nous allons
chercher à savoir si **deux variables quantitatives sont liées entre elles**.

Par exemple :

> **Lorsque la valeur d'une variable X augmente, la variable Y a-t-elle
> tendance à augmenter, à diminuer ou à rester indépendante de X ?**

Pour répondre à cette question, nous utiliserons des graphiques et plusieurs
indicateurs statistiques.

---

# 🎯 Objectifs du TD

À la fin de ce TD, vous devrez être capable de :

- distinguer une approche **descriptive** d'une approche **explicative** ;
- formuler une hypothèse sur la relation entre deux variables ;
- identifier une variable **X** et une variable **Y** ;
- construire et interpréter un **nuage de points** ;
- calculer et interpréter la **covariance** ;
- calculer et interpréter le **coefficient de corrélation de Bravais-Pearson (r)** ;
- comprendre le principe d'une **régression linéaire** ;
- interpréter une équation de la forme **Y = aX + b** ;
- interpréter le **coefficient de détermination R²** ;
- repérer des **valeurs exceptionnelles (outliers)** ;
- calculer et interpréter les **résidus** ;
- reconnaître différentes formes de relations entre deux variables.

---

# 🧭 Ce que nous allons apprendre

L'analyse d'une relation entre deux variables quantitatives suit plusieurs
étapes.

## 1. Passer d'une variable à deux variables

Dans le TD1, nous étudiions une variable indépendamment des autres.

Nous allons maintenant travailler simultanément sur **deux variables
quantitatives** afin de déterminer si elles évoluent ensemble.

On distingue notamment :

- les **méthodes descriptives**, qui permettent d'organiser, représenter
  et résumer les données ;
- les **méthodes explicatives**, qui cherchent à comprendre les variations
  d'une variable à l'aide d'une autre variable.

> 💡 **Question centrale du TD :**
> lorsque **X varie**, est-ce que **Y varie également** ?

---

## 2. Poser une hypothèse

Avant de réaliser les calculs, il faut formuler une question ou une
**hypothèse**.

Par exemple :

> Plus une variable X augmente, plus une variable Y augmente-t-elle ?

On distingue alors généralement :

- **X** : la variable indépendante ou explicative ;
- **Y** : la variable dépendante, c'est-à-dire celle que l'on cherche
  à expliquer ou à prédire.

L'objectif est ensuite de vérifier si les données sont compatibles avec
l'hypothèse formulée.

---

## 3. Explorer graphiquement la relation

La première étape consiste à construire un **nuage de points**.

Chaque individu est représenté par un point :

- sa valeur de **X** détermine sa position sur l'axe horizontal ;
- sa valeur de **Y** détermine sa position sur l'axe vertical.

Le nuage permet d'observer rapidement si les deux variables semblent
évoluer ensemble.

On peut notamment rencontrer :

- une liaison linéaire positive ;
- une liaison linéaire négative ;
- une liaison monotone mais non linéaire ;
- une liaison non monotone et non linéaire ;
- une absence apparente de liaison.

> 💡 **À retenir :**
> avant de calculer un coefficient, commencez toujours par **regarder le
> nuage de points**.

---

## 4. Mesurer la relation : covariance et corrélation

Après l'observation graphique, nous pouvons mesurer numériquement la relation.

### La covariance

La **covariance** permet de déterminer si deux variables ont tendance
à évoluer ensemble.

Elle renseigne notamment sur le **sens de leur variation commune**.

### Le coefficient de corrélation

Le **coefficient de corrélation de Bravais-Pearson**, noté **r**, permet
d'étudier une **relation linéaire** entre deux variables quantitatives.

Sa valeur est comprise entre **-1 et +1**.

- **r proche de +1** → forte relation linéaire positive ;
- **r proche de -1** → forte relation linéaire négative ;
- **r proche de 0** → absence ou faiblesse de la relation linéaire.

> ⚠️ **Attention :**
> un coefficient proche de 0 ne signifie pas nécessairement qu'il n'existe
> aucune relation entre X et Y. Une relation peut être **non linéaire**.

---

## 5. Modéliser la relation : la régression linéaire

Lorsque le nuage de points montre une relation approximativement linéaire,
nous pouvons chercher à la représenter par une droite.

Le modèle étudié dans ce TD est :

**Y = aX + b**

avec :

- **Y** : la variable que l'on cherche à expliquer ou à prédire ;
- **X** : la variable explicative ;
- **a** : la pente de la droite ;
- **b** : l'ordonnée à l'origine.

La pente **a** indique comment Y évolue lorsque X augmente.

> 💡 **Idée importante :**
> la droite de régression résume la **tendance générale** observée dans
> le nuage de points.

---

## 6. Interpréter le coefficient de détermination R²

Le **coefficient de détermination R²** permet d'évaluer dans quelle mesure
le modèle linéaire rend compte des variations de Y.

R² varie entre **0 et 1**.

Par exemple : **R² = 0,60**

signifie que le modèle linéaire rend compte de **60 % de la variation de Y**
dans les données étudiées.

Plus R² est proche de 1, plus les points sont cohérents avec le modèle
linéaire utilisé.

> ⚠️ Un R² élevé ne suffit pas à démontrer qu'une variable est la
> **cause** de l'autre.

---

## 7. Repérer les valeurs exceptionnelles

Une **valeur exceptionnelle**, ou *outlier*, est une observation qui se
situe très loin des autres observations.

Dans un nuage de points, elle apparaît généralement comme un point isolé
ou très éloigné de la tendance générale.

Ces observations peuvent fortement modifier :

- la droite de régression ;
- la corrélation ;
- le coefficient R² ;
- l'interprétation finale.

> 💡 **À retenir :**
> une valeur exceptionnelle doit d'abord être **repérée et comprise**.
> Sa présence peut avoir une influence importante sur les résultats.

---

## 8. Comprendre les résidus

Une droite de régression représente une tendance générale, mais les points
ne se trouvent généralement pas exactement sur cette droite.

La différence entre la **valeur observée** et la **valeur prédite par le
modèle** constitue le **résidu**.

### Résidu positif

La valeur observée est **supérieure** à la valeur prédite par le modèle.

### Résidu négatif

La valeur observée est **inférieure** à la valeur prédite par le modèle.

Nous distinguerons :

- les **résidus bruts (RB)** ;
- les **résidus relatifs (RR)**, exprimés en pourcentage.

L'analyse des résidus permet notamment de vérifier si le modèle linéaire
est adapté aux données.

---

# 🔎 Démarche à retenir

Pour étudier la relation entre deux variables quantitatives, adoptez
progressivement la démarche suivante :

**1. Poser une hypothèse**

↓  

**2. Identifier X et Y**

↓  

**3. Construire le tableau de données**

↓  

**4. Observer le nuage de points**

↓  

**5. Calculer la covariance et la corrélation**

↓  

**6. Construire et interpréter la régression**

↓  

**7. Examiner R² et les valeurs exceptionnelles**

↓  

**8. Calculer et interpréter les résidus**

↓  

**9. Interpréter les résultats dans leur contexte**

---

# 📄 Support de cours

Le support présente les différentes étapes nécessaires pour analyser la
relation entre deux variables quantitatives :

- méthodes descriptives et explicatives ;
- hypothèse et choix des variables ;
- nuage de points ;
- covariance ;
- corrélation de Bravais-Pearson ;
- régression linéaire ;
- coefficient de détermination R² ;
- valeurs exceptionnelles ;
- résidus ;
- formes des nuages de points.

👉 [**Télécharger le support - Relation entre deux variables quantitatives (PDF)**](documents/TD2/Relation_entre_deux_variables_quantitatives.pdf)
 
---

# ✏️ Données et énoncé du TD

Le dossier contient **l'énoncé du TD et les données nécessaires aux
exercices**.

👉 [**Télécharger le TD2 - Énoncé et données (ZIP)**](documents/TD2/TD2.zip)

<div style="background-color:#fdecea; border-left:4px solid #c0392b; padding:10px 15px; margin:10px 0;">
<strong style="color:#c0392b;">⚠️ Important :</strong>
le fichier téléchargé est au format ZIP. Il ne s'ouvrira pas directement
dans Excel. Après le téléchargement, vous devez d'abord
<strong>décompresser le fichier</strong> sur votre ordinateur pour accéder
à l'énoncé et aux données.
</div>

---

# ✅ Correction du TD

La correction est disponible au format Excel.

Elle vous permettra de vérifier vos calculs, vos graphiques et
l'interprétation de vos résultats.

👉 [**Télécharger la correction du TD2 (Excel)**](documents/TD2/TD2_Corrige.xlsx)

> ⚠️ Essayez de réaliser les exercices avant de consulter la correction.

---

# 🧠 Ce qu'il faut retenir

À l'issue de ce TD, vous devez être capable de vous poser les questions
suivantes :

**Existe-t-il une relation entre X et Y ?**

**Dans quel sens les deux variables évoluent-elles ?**

**La relation observée est-elle linéaire ?**

**Quelle est la force de la relation linéaire ?**

**La droite de régression représente-t-elle correctement les données ?**

**Existe-t-il des observations exceptionnelles ?**

**Que nous apprennent les résidus ?**

Enfin, gardez toujours en mémoire une règle fondamentale :

> **Une relation statistique entre deux variables ne signifie pas
> nécessairement que l'une est la cause de l'autre.**

L'interprétation statistique doit toujours être replacée dans le
**contexte géographique et thématique** de l'étude.

---

# ➡️ Pour aller plus loin

Dans ce TD, nous nous sommes principalement intéressés à la
**relation linéaire** entre deux variables quantitatives.

Le TD suivant permettra d'étudier une situation dans laquelle deux variables
peuvent être liées sans que leur relation soit correctement représentée
par une droite.

👉 [**Continuer vers le TD3 - Relation quanti-quanti non linéaire**](03_TD3_Relation_Non_Lineaire.html)
