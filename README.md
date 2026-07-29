# Statistiques et cartographie — Site du cours

Site pédagogique généré avec Jekyll (thème "Read the Docs"), prêt à être publié
gratuitement sur GitHub Pages.

## Comment publier ce site (une seule fois)

1. Va sur https://github.com/new et crée un nouveau dépôt (repository) sous ton
   compte **KadjoRaphael**.
   - Nom suggéré : `stats_cartographie`
   - Laisse-le public
   - Ne coche pas "Add a README" (on en a déjà un)

2. Sur ton ordinateur, ouvre un terminal dans ce dossier (`statistiques_cartographie`)
   et tape ces commandes (remplace `stats_cartographie` par le nom choisi si différent) :

   ```bash
   git init
   git add .
   git commit -m "Premier commit du site du cours"
   git branch -M main
   git remote add origin https://github.com/KadjoRaphael/stats_cartographie.git
   git push -u origin main
   ```

3. Sur GitHub, va dans les **Settings** du dépôt > **Pages** (menu de gauche).
   - Source : `Deploy from a branch`
   - Branch : `main`, dossier `/ (root)`
   - Clique sur **Save**

4. Après 1 à 2 minutes, ton site sera disponible à l'adresse :
   `https://kadjoraphael.github.io/stats_cartographie/`

## Comment ajouter du contenu ensuite

- Chaque page est un simple fichier `.md` (Markdown) à la racine du dossier.
- Pour ajouter un support de cours en PDF ou un jeu de données : crée un dossier
  `documents/` (ou `data/`), dépose le fichier dedans, puis ajoute un lien dans
  la page Markdown correspondante, par exemple :

  ```markdown
  [Support de cours TD1](documents/TD1_support.pdf)
  ```

- Après chaque modification :

  ```bash
  git add .
  git commit -m "Description de la modification"
  git push
  ```

  Le site se met à jour automatiquement en 1-2 minutes.

## Structure actuelle

```
00_Introduction.md                     -> page d'accueil / programme
01_TD1_Statistique_Univariee.md        -> Séances 1-2
02_TD2_Relation_Quanti_Quanti.md       -> Séances 3-4
03_TD3_Relation_Non_Lineaire.md        -> Séances 5-6
04_TD4_Relation_Quali_Quali.md         -> Séances 7-8
05_TD5_Erreur_Ecologique.md            -> Séance 9
06_TD6_Relation_Quali_Quanti.md        -> Séances 11-12
07_Devoir_Sur_Table.md                 -> Séance 10 (+ correction en séance 11)
```

Chaque page TD contient des sections à compléter : objectifs, support de cours,
données, énoncé, correction.
