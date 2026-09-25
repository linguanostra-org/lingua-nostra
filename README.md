# Lingua Nostra

Outils libres pour le provençal en graphie mistralienne : dictionnaires, outils de traitement automatique du langage (TAL) et modèle de langue Lou Pichoun.

Porteur : LINGUA NOSTRA SASU (SIRET 108 870 809 00010). Site : https://linguanostra.org

Lingua Nostra publie ici, à sa discrétion, le plus grand nombre possible de ses outils.

## Contenu prévu

### 1. Dictionnaire

- `lexique/` : lexique monolingue provençal pour les claviers et les correcteurs orthographiques (formats Hunspell, Windows, Android).
- `dictionnaire/` : chaîne de construction du dictionnaire bilingue provençal-français servi sur linguanostra.org.
- `conjugaison/` : conjugueur selon les règles du Conseil de l'Écrit Mistralien.

### 2. Outils de traitement automatique du langage

- `tal/identifieur/` : identifieur de langue, qui reconnaît le provençal en graphie mistralienne.
- `tal/tokeniseur/` : tokeniseur adapté à la graphie mistralienne.
- `tal/lemmatiseur/` : lemmatiseur, qui ramène chaque forme à sa vedette de dictionnaire.
- `tal/analyseur/` : analyseur morphologique (genre, nombre, personne, temps, mode).
- Jeux de test validés par des locuteurs natifs, pour chacun des quatre outils.

### 3. Lou Pichoun

- `lou-pichoun/` : code d'entraînement, d'affinage et d'évaluation du modèle de langue provençal Lou Pichoun.
- Les poids du modèle seront publiés sur Hugging Face.

Les données sources soumises à droits restent hors du dépôt ; seuls le code et les données dont la licence le permet y sont publiés.

## Licence

Code sous licence Apache 2.0 (voir `LICENSE`).

---

# Lingua Nostra (English)

Free and open source tools for Provençal in Mistralian spelling: dictionaries, natural language processing (NLP) tools, and the Lou Pichoun language model.

Lingua Nostra publishes here, at its discretion, as many of its tools as possible.

## Planned content

### 1. Dictionary

- `lexique/`: monolingual Provençal lexicon for keyboards and spell checkers (Hunspell, Windows, Android formats).
- `dictionnaire/`: build pipeline for the bilingual Provençal-French dictionary served on linguanostra.org.
- `conjugaison/`: conjugator following the rules of the Conseil de l'Écrit Mistralien.

### 2. Natural language processing tools

- `tal/identifieur/`: language identifier for Provençal in Mistralian spelling.
- `tal/tokeniseur/`: tokenizer adapted to Mistralian spelling.
- `tal/lemmatiseur/`: lemmatizer mapping each form to its dictionary headword.
- `tal/analyseur/`: morphological analyzer (gender, number, person, tense, mood).
- Test sets validated by native speakers for each of the four tools.

### 3. Lou Pichoun

- `lou-pichoun/`: training, fine-tuning and evaluation code for the Provençal language model Lou Pichoun.
- Model weights will be published on Hugging Face.

Source data under third-party rights stays out of this repository; only code and data whose licence allows it are published.

## Licence

Code licensed under Apache 2.0 (see `LICENSE`).
