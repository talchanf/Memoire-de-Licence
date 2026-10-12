# Mémoire de Licence : santé mentale des joueurs de jeux vidéo en ligne

**La santé mentale des joueurs de jeux vidéo en ligne : comparaison entre pratiques compétitives et non compétitives.**

Mémoire de L3 MIASHS (mineure psychologie), Université Lumière Lyon 2, année 2025-2026.

## Question de recherche

Les joueurs qui pratiquent le jeu vidéo en compétition présentent-ils une santé mentale différente de ceux qui jouent hors compétition ? Le travail examine aussi le rôle de l'engagement, de la toxicité vécue en ligne, du genre, du sommeil et de l'âge.

## Méthode

Démarche en deux phases :

1. **Phase exploratoire** : test du protocole et des outils de mesure, qui a mis en évidence des limites et orienté la suite.
2. **Phase finale** : protocole ajusté (ajout de mesures de la toxicité perçue et du sommeil), questionnaire diffusé en ligne sur des groupes et forums de joueurs.

Échelles utilisées :

- **STAI-Y** (Spielberger) : anxiété-état (Y1) et anxiété-trait (Y2)
- **WHO-5** : bien-être
- **Échelle de Rosenberg** : estime de soi
- Questions sur la pratique de jeu, la toxicité subie et le sommeil

Sept hypothèses de recherche sont testées.

## Analyses statistiques

Collecte avec Google Forms, préparation dans Excel, analyses sous **R** : statistiques descriptives, tests t de Student, ANOVA à deux facteurs, corrélations de Pearson, régressions multiples, analyses de médiation.

## Contenu du dépôt

| Fichier | Contenu |
|---|---|
| `memoire_Furnon_2236524.docx` | Le mémoire complet |
| `données.zip` | Le tableau de données final et les scripts R |

Les scripts R, dans `données/code r/` après décompression, sont organisés par mesure : `STAI-Y1 ÉTAT.R`, `STAI-Y2 TRAIT.R`, `WHO-5.R`, `ROSENBERG.R`, `toxicite.R`, `frequence.R`, `age.R`, `genre.R`.

## Reproduire les analyses

1. Décompresser `données.zip`.
2. Ouvrir un script dans RStudio.
3. Adapter le chemin vers `tableau fin mémoire.xlsx` si besoin, puis exécuter.

## Limites

Le recrutement par convenance expose à un biais de sélection, les mesures sont auto-déclarées, et le moment de passation du questionnaire n'est pas contrôlé. Ces limites sont discutées dans le mémoire.
