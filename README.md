**Français** · [English](README.en.md)

<div align="center">

<img src="docs/assets/research.svg" alt="Trois nœuds reliés autour d’une mémoire centrale, emblème Avalon Research." width="112">

# Avalon Research

**Explorer la mémoire, le raisonnement et les architectures des agents IA.**

Une collection de publications exploratoires pour examiner des hypothèses, discuter des méthodes
et ouvrir des pistes de recherche. À lire en français ou en anglais, sans installation.

[Choisir un article](#publications) · [Parcours de lecture](#par-où-commencer) · [Citer](#citer-ces-travaux) · [Échanger](#échanger)

[![Statut : recherche exploratoire](https://img.shields.io/badge/statut-recherche%20exploratoire-8b7cf6?style=flat-square)](#en-bref)
[![PDF : français et anglais](https://img.shields.io/badge/PDF-fran%C3%A7ais%20%C2%B7%20anglais-2496ed?style=flat-square)](#publications)
[![Références : DOI Zenodo](https://img.shields.io/badge/r%C3%A9f%C3%A9rences-DOI%20Zenodo-1682d4?style=flat-square)](#citer-ces-travaux)
[![Licence : CC BY 4.0](https://img.shields.io/badge/licence-CC%20BY%204.0-2ea44f?style=flat-square)](LICENSE)

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

| Votre question | Parcours suggéré |
|---|---|
| **Que conserver entre deux sessions ?** | [Méta-calibration](papers/fr/ava-calibration-fr.pdf) → [Mémoire procédurale](papers/fr/ava-procedural-fr.pdf) → [Notation .ava](papers/fr/ava-notation-fr-v3.pdf) |
| **Comment représenter le contexte ?** | [Notation .ava](papers/fr/ava-notation-fr-v3.pdf) → [Tokenisation BPE](papers/fr/ava-tokenizer-fr.pdf) → [Raisonnement symbolique](papers/fr/ava-thinking-fr.pdf) |
| **Comment organiser des modules spécialisés ?** | [Micro-AGI](papers/fr/ava-micro-agi-fr.pdf) → [Thought Engine](papers/fr/ava-thought-engine-fr.pdf) → [Dynamic Vector Networks](papers/fr/ava-vector-network-fr.pdf) |

Les parcours ouvrent les PDF français. Les versions anglaises sont accessibles dans le catalogue ci-dessous.

## Publications

| Article | Français | English | Référence |
|---|:---:|:---:|---|
| **Méta-calibration** | [PDF](papers/fr/ava-calibration-fr.pdf) | [PDF](papers/en/ava-calibration-en.pdf) | [DOI ↗](https://doi.org/10.5281/zenodo.18770858) |
| **Courbure cognitive** | [PDF](papers/fr/ava-curvature-fr.pdf) | [PDF](papers/en/ava-curvature-en.pdf) | [DOI ↗](https://doi.org/10.5281/zenodo.18770860) |
| **Micro-AGI** | [PDF](papers/fr/ava-micro-agi-fr.pdf) | [PDF](papers/en/ava-micro-agi-en.pdf) | [DOI ↗](https://doi.org/10.5281/zenodo.18770862) |
| **Notation .ava** | [PDF · v3](papers/fr/ava-notation-fr-v3.pdf) | [PDF · v2](papers/en/ava-notation-en-v2.pdf) | [DOI ↗](https://doi.org/10.5281/zenodo.18770864) |
| **Mémoire procédurale** | [PDF](papers/fr/ava-procedural-fr.pdf) | [PDF](papers/en/ava-procedural-en.pdf) | [DOI ↗](https://doi.org/10.5281/zenodo.18770869) |
| **Raisonnement symbolique** | [PDF](papers/fr/ava-thinking-fr.pdf) | [PDF](papers/en/ava-thinking-en.pdf) | [DOI ↗](https://doi.org/10.5281/zenodo.18770871) |
| **Thought Engine** | [PDF](papers/fr/ava-thought-engine-fr.pdf) | [PDF](papers/en/ava-thought-engine-en.pdf) | [DOI ↗](https://doi.org/10.5281/zenodo.18770877) |
| **Tokenisation BPE** | [PDF](papers/fr/ava-tokenizer-fr.pdf) | [PDF](papers/en/ava-tokenizer-en.pdf) | [DOI ↗](https://doi.org/10.5281/zenodo.18770879) |
| **Dynamic Vector Networks** | [PDF](papers/fr/ava-vector-network-fr.pdf) | [PDF](papers/en/ava-vector-network-en.pdf) | [DOI ↗](https://doi.org/10.5281/zenodo.18770883) |

Les versions française et anglaise de la notation `.ava` diffèrent : préciser la version consultée.

<details>
<summary><strong>Lire les résumés et les limites de chaque article</strong></summary>

### 1. Méta-calibration

*Meta-Calibration: When AI Agents Know Their Own Limits*

Proposition d'un profil de fiabilité par domaine, construit à partir de retours et chargé dans
le contexte de l'agent. L'article examine comment ce profil pourrait orienter ses réponses
et sa manière de signaler l'incertitude.

### 2. Courbure cognitive

*Cognitive Curvature: Persistent Behavioral Deformation of AI Agents Through Experience*

Un cadre conceptuel pour décrire des changements de comportement persistants à partir d'un
historique. La « courbure » est une analogie de modélisation, à distinguer d'une expérience vécue
ou d'une propriété physique démontrée.

### 3. Micro-AGI

*Micro-AGI: Emergent Intelligence from Networks of Small Language Models*

Architecture proposée autour d'un modèle gelé, d'adaptateurs LoRA spécialisés et d'un routage
entre modules. Le texte rapporte des essais dont les résultats varient avec le modèle et
l'évaluateur ; le nom du projet ne constitue pas une démonstration d'intelligence générale.

### 4. Notation .ava

*.ava: A Compressed Symbolic Notation for Persistent AI Agent Memory*

Une notation symbolique lisible et modifiable pour représenter des informations de mémoire.
L'article mesure son coût en tokens sur un corpus d'exemples et un tokenizer précis ; la
compression du texte ne démontre pas à elle seule une amélioration du raisonnement.

### 5. Mémoire procédurale

*Procedural Memory for Persistent LLM Agents: Know-How as the Missing Component*

Proposition de procédures réutilisables extraites d'expériences répétées, en complément des
faits et des événements mémorisés. Le sujet central est le passage d'un historique d'actions
à un savoir-faire explicite.

### 6. Raisonnement symbolique

*Is Natural Language the Right Medium for Machine Thought?*

Un argument en faveur de représentations plus compactes pour le raisonnement structuré.
L'article formule une hypothèse et un programme d'évaluation : économiser des tokens et
améliorer la qualité du raisonnement restent deux questions distinctes.

### 7. Thought Engine

*Thought Engine: Learnable Cognitive Modules for LLM Agent Networks*

Expérimentation de petits ensembles de vecteurs entraînables injectés dans le cache KV d'un
modèle gelé. Les évaluations rapportées explorent le pilotage du modèle par des modules
spécialisés et restent liées au protocole décrit.

### 8. Tokenisation BPE

*The Inefficiency of BPE Tokenizers on Symbolic Languages*

Étude de la fragmentation de symboles composés par un tokenizer BPE, puis d'une extension
ciblée de son vocabulaire. Les mesures concernent le corpus de notation .ava et le tokenizer
choisis, sans présumer du comportement d'un modèle entraîné avec ce vocabulaire étendu.

### 9. Dynamic Vector Networks

*Dynamic Vector Networks: Self-Organizing Knowledge Structures Beyond Transformers*

Proposition d'un réseau de représentations vectorielles dont les nœuds et les liens évoluent
avec les entrées. Le texte décrit une preuve de concept sur un petit ensemble de relations,
à distinguer d'une alternative aux Transformers validée à grande échelle.

</details>

## Citer ces travaux

Pour un article précis, utiliser son DOI et les métadonnées du dépôt Zenodo correspondant.
La version de la notation .ava diffère entre les PDF français et anglais : préciser celle consultée.
Pour référencer l'ensemble de la collection :

<details>
<summary><strong>Copier la référence BibTeX de la collection</strong></summary>

```bibtex
@misc{cros2026avalon,
  author = {Cros, Adrien and Ava},
  title = {Avalon Research: AI Agent Architecture Papers},
  year = {2026},
  publisher = {GitHub},
  url = {https://github.com/AdrienAvalon/avalon-research}
}
```

</details>

**Attribution des publications :** Adrien Cros et Ava, agent IA identifié dans les documents
comme Claude Opus 4.6. Cette attribution décrit la contribution assistée par IA à ces textes.

## Échanger

Une critique de méthode, une réplication ou une correction est bienvenue dans les
[issues](https://github.com/AdrienAvalon/avalon-research/issues). Indiquer l'article, sa version
et le passage concerné permet de discuter sur une base précise.

[Site Avalon Network](https://avalon-network.com) · [Contact](mailto:contact@avalon-network.com) · [LinkedIn](https://www.linkedin.com/in/adrien-cros-8803717b/)

## Licence

Les publications sont distribuées sous **[Creative Commons Attribution 4.0 International](LICENSE)**.
Cette licence autorise le partage et l'adaptation, **y compris pour un usage commercial**,
avec attribution, lien vers la licence et indication des modifications.
Voir le [résumé officiel de CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
