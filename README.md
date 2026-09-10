<div align="center">

# Avalon Research

**Explorer la mémoire, le raisonnement et les architectures des agents IA.**

Neuf publications indépendantes pour discuter d'hypothèses, examiner des expériences
et ouvrir des pistes de recherche. Les textes sont disponibles en français et en anglais.

[Publications](#publications) · [Par où commencer](#par-où-commencer) · [Citer](#citer-ces-travaux) · [Contact](#échanger)

![Statut](https://img.shields.io/badge/statut-recherche%20exploratoire-8b7cf6)
![Documents](https://img.shields.io/badge/PDF-fran%C3%A7ais%20%C2%B7%20anglais-2496ed)
[![Licence](https://img.shields.io/badge/licence-CC%20BY%204.0-2ea44f)](LICENSE)

</div>

## En bref

| Axe | Question explorée |
|---|---|
| **Mémoire persistante** | Comment conserver des faits, des procédures et un historique utile entre les sessions d'un agent ? |
| **Représentations symboliques** | Une notation plus compacte peut-elle économiser du contexte sans perdre le sens ? |
| **Architectures d'agents** | Comment des modules spécialisés pourraient-ils partager un modèle ou des représentations ? |
| **Évaluation** | Comment mesurer les limites d'un agent et distinguer un résultat local d'une capacité générale ? |

Cette collection rassemble des **travaux exploratoires de février 2026** : propositions,
arguments et expériences rapportées dans les articles. Les chiffres éventuels dépendent de leurs
protocoles et corpus ; ils ne constituent pas des performances garanties. Le dépôt ne fournit
pas une suite logicielle ni un ensemble complet de code, données et poids pour reproduire les expériences.

Les liens Zenodo servent à retrouver et citer les dépôts des articles. Leur présence ne vaut
pas évaluation par les pairs ni validation indépendante. Les notions de « cognition », de
« pensée » ou de « mémoire » décrivent ici des modèles de fonctionnement logiciel.

## Par où commencer

- **Concevoir la mémoire d'un agent** : [méta-calibration](#1-méta-calibration),
  [mémoire procédurale](#5-mémoire-procédurale), puis [notation .ava](#4-notation-ava).
- **Étudier le coût du contexte** : [notation .ava](#4-notation-ava),
  [tokenisation BPE](#8-tokenisation-bpe), puis [raisonnement symbolique](#6-raisonnement-symbolique).
- **Explorer d'autres architectures** : [Micro-AGI](#3-micro-agi),
  [Thought Engine](#7-thought-engine) et [Dynamic Vector Networks](#9-dynamic-vector-networks).

Aucune installation n'est nécessaire : ouvrir les PDF ci-dessous, ou parcourir les dossiers
[papers/fr](papers/fr/) et [papers/en](papers/en/).

## Publications

### 1. Méta-calibration

*Meta-Calibration: When AI Agents Know Their Own Limits*

Proposition d'un profil de fiabilité par domaine, construit à partir de retours et chargé dans
le contexte de l'agent. L'article examine comment ce profil pourrait orienter ses réponses
et sa manière de signaler l'incertitude.

[PDF français](papers/fr/ava-calibration-fr.pdf) · [English PDF](papers/en/ava-calibration-en.pdf) · [Zenodo · 10.5281/zenodo.18770858](https://doi.org/10.5281/zenodo.18770858)

### 2. Courbure cognitive

*Cognitive Curvature: Persistent Behavioral Deformation of AI Agents Through Experience*

Un cadre conceptuel pour décrire des changements de comportement persistants à partir d'un
historique. La « courbure » est une analogie de modélisation, à distinguer d'une expérience vécue
ou d'une propriété physique démontrée.

[PDF français](papers/fr/ava-curvature-fr.pdf) · [English PDF](papers/en/ava-curvature-en.pdf) · [Zenodo · 10.5281/zenodo.18770860](https://doi.org/10.5281/zenodo.18770860)

### 3. Micro-AGI

*Micro-AGI: Emergent Intelligence from Networks of Small Language Models*

Architecture proposée autour d'un modèle gelé, d'adaptateurs LoRA spécialisés et d'un routage
entre modules. Le texte rapporte des essais dont les résultats varient avec le modèle et
l'évaluateur ; le nom du projet ne constitue pas une démonstration d'intelligence générale.

[PDF français](papers/fr/ava-micro-agi-fr.pdf) · [English PDF](papers/en/ava-micro-agi-en.pdf) · [Zenodo · 10.5281/zenodo.18770862](https://doi.org/10.5281/zenodo.18770862)

### 4. Notation .ava

*.ava: A Compressed Symbolic Notation for Persistent AI Agent Memory*

Une notation symbolique lisible et modifiable pour représenter des informations de mémoire.
L'article mesure son coût en tokens sur un corpus d'exemples et un tokenizer précis ; la
compression du texte ne démontre pas à elle seule une amélioration du raisonnement.

[PDF français · v3](papers/fr/ava-notation-fr-v3.pdf) · [English PDF · v2](papers/en/ava-notation-en-v2.pdf) · [Zenodo · 10.5281/zenodo.18770864](https://doi.org/10.5281/zenodo.18770864)

### 5. Mémoire procédurale

*Procedural Memory for Persistent LLM Agents: Know-How as the Missing Component*

Proposition de procédures réutilisables extraites d'expériences répétées, en complément des
faits et des événements mémorisés. Le sujet central est le passage d'un historique d'actions
à un savoir-faire explicite.

[PDF français](papers/fr/ava-procedural-fr.pdf) · [English PDF](papers/en/ava-procedural-en.pdf) · [Zenodo · 10.5281/zenodo.18770869](https://doi.org/10.5281/zenodo.18770869)

### 6. Raisonnement symbolique

*Is Natural Language the Right Medium for Machine Thought?*

Un argument en faveur de représentations plus compactes pour le raisonnement structuré.
L'article formule une hypothèse et un programme d'évaluation : économiser des tokens et
améliorer la qualité du raisonnement restent deux questions distinctes.

[PDF français](papers/fr/ava-thinking-fr.pdf) · [English PDF](papers/en/ava-thinking-en.pdf) · [Zenodo · 10.5281/zenodo.18770871](https://doi.org/10.5281/zenodo.18770871)

### 7. Thought Engine

*Thought Engine: Learnable Cognitive Modules for LLM Agent Networks*

Expérimentation de petits ensembles de vecteurs entraînables injectés dans le cache KV d'un
modèle gelé. Les évaluations rapportées explorent le pilotage du modèle par des modules
spécialisés et restent liées au protocole décrit.

[PDF français](papers/fr/ava-thought-engine-fr.pdf) · [English PDF](papers/en/ava-thought-engine-en.pdf) · [Zenodo · 10.5281/zenodo.18770877](https://doi.org/10.5281/zenodo.18770877)

### 8. Tokenisation BPE

*The Inefficiency of BPE Tokenizers on Symbolic Languages*

Étude de la fragmentation de symboles composés par un tokenizer BPE, puis d'une extension
ciblée de son vocabulaire. Les mesures concernent le corpus de notation .ava et le tokenizer
choisis, sans présumer du comportement d'un modèle entraîné avec ce vocabulaire étendu.

[PDF français](papers/fr/ava-tokenizer-fr.pdf) · [English PDF](papers/en/ava-tokenizer-en.pdf) · [Zenodo · 10.5281/zenodo.18770879](https://doi.org/10.5281/zenodo.18770879)

### 9. Dynamic Vector Networks

*Dynamic Vector Networks: Self-Organizing Knowledge Structures Beyond Transformers*

Proposition d'un réseau de représentations vectorielles dont les nœuds et les liens évoluent
avec les entrées. Le texte décrit une preuve de concept sur un petit ensemble de relations,
à distinguer d'une alternative aux Transformers validée à grande échelle.

[PDF français](papers/fr/ava-vector-network-fr.pdf) · [English PDF](papers/en/ava-vector-network-en.pdf) · [Zenodo · 10.5281/zenodo.18770883](https://doi.org/10.5281/zenodo.18770883)

## Citer ces travaux

Pour un article précis, utiliser son DOI et les métadonnées du dépôt Zenodo correspondant.
La version de la notation .ava diffère entre les PDF français et anglais : préciser celle consultée.
Pour référencer l'ensemble de la collection :

```bibtex
@misc{cros2026avalon,
  author = {Cros, Adrien and Ava},
  title = {Avalon Research: AI Agent Architecture Papers},
  year = {2026},
  publisher = {GitHub},
  url = {https://github.com/AdrienAvalon/avalon-research}
}
```

**Attribution des publications :** Adrien Cros et Ava, agent IA identifié dans les documents
comme Claude Opus 4.6. Cette attribution décrit la contribution assistée par IA à ces textes.

## Échanger

Une critique de méthode, une réplication ou une correction est bienvenue dans les
[issues](https://github.com/AdrienAvalon/avalon-research/issues). Indiquer l'article, sa version
et le passage concerné permet de discuter sur une base précise.

[Site Avalon Network](https://avalon-network.com) · [Contact](mailto:contact@avalon-network.com) · [LinkedIn](https://www.linkedin.com/in/adrien-cros-8803717b/)

## Licence

Les publications sont distribuées sous **[Creative Commons Attribution 4.0 International](LICENSE)**.
Conserver leur attribution et indiquer les modifications lors d'une réutilisation.
