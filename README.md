# InformsLabs

[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-blue.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-blue.svg)](CONTRIBUTING.md)
[![Site Web](https://img.shields.io/badge/Site-InformsLabs-blue?logo=github)](https://teremuhamblin.github.io/InformsLabs/)

> Une sélection de référence des meilleurs outils, bases de données et plateformes dédiés à l'**informatique des matériaux** (*Materials Informatics*).

---

## 🔬 Qu'est-ce que l'informatique des matériaux ?

L'**informatique des matériaux** se situe au carrefour de la science des matériaux, de l'intelligence artificielle et de la science des données. Elle accélère la découverte et la conception de nouveaux matériaux en associant les méthodes de simulation physique (*ab initio*, DFT, dynamique moléculaire) aux approches d'apprentissage automatique (*Machine Learning*).

---

## 📑 Sommaire

- [Logiciels et bibliothèques](#-logiciels-et-bibliothèques)
  - [Simulation et gestion de flux de calcul](#simulation--gestion-de-flux-de-calcul-workflows)
  - [Graphes de neurones et potentiels d'apprentissage (MLIP)](#graphes-de-neurones-et-potentiels-dapprentissage-mlip)
  - [Analyse et apprentissage automatique](#analyse--machine-learning-appliqué-aux-matériaux)
- [Modèles de fondation et initiatives IA](#-modèles-de-fondation-et-initiatives-ia)
- [Bases de données de matériaux](#-bases-de-données-de-matériaux)
- [Standards et interopérabilité](#-standards-et-interopérabilité)
- [Contribution et Licence](#-contribution-et-licence)

---

## 🛠 Logiciels et bibliothèques

### Simulation & Gestion de flux de calcul (Workflows)
* [AiiDA](http://aiida.net) (**Python**) – Automatisation des calculs *ab initio* et traçabilité complète des données avec graphes de provenance.
* [ASE](https://wiki.fysik.dtu.dk/ase) (**Python**) – Environnement standard de configuration, manipulation et simulation atomistique.
* [atomate2](https://github.com/materialsproject/atomate2) & [jobflow](https://github.com/materialsproject/jobflow) (**Python**) – La nouvelle génération de bibliothèques d'orchestration de calculs DFT et matériaux (successeurs de *FireWorks* et *atomate*).
* [quacc](https://github.com/arosen93/quacc) (**Python**) – Plateforme moderne et modulaire de calculs haut débit pour la chimie quantique et l'état solide.

### Graphes de neurones et potentiels d'apprentissage (MLIP)
* [MACE](https://github.com/ACEsuit/mace) (**Python / PyTorch**) – Architecture de potentiels interatomiques équivariants de référence pour la dynamique moléculaire rapide et précise.
* [CHGNet](https://github.com/C-PAC/chgnet) (**Python**) – Potentiel universel basé sur les réseaux de neurones sur graphes prenant en compte les interactions électroniques et orbitales.
* [matgl](https://github.com/materialsproject/matgl) (**Python**) – *Materials Graph Library* (par l'équipe du Materials Project), implémentant des modèles MEGNet et M3GNet.
* [ALIGNN](https://github.com/usnistgov/alignn) (**Python**) – Réseau sur graphes modélisant explicitement les angles de liaison, développé par le NIST.

### Analyse & Machine Learning appliqué aux matériaux
* [Pymatgen](https://pymatgen.org) (**Python**) – Bibliothèque open source de référence pour l'analyse structurale, thermodynamique et cristallographique.
* [matminer](https://github.com/hackingmaterials/matminer) (**Python**) – Extraction de descripteurs (*featurization*) et fouille de données pour les structures cristallines et compositions.
* [CDVAE](https://github.com/txie-93/cdvae) (**Python**) – Modèle génératif (auto-encodeur variationnel à diffusion) pour la conception inverse de cristaux périodiques.
* [CrabNet](https://github.com/anthony-wang/CrabNet) (**Python**) – Prédiction rapide de propriétés physiques à partir de la seule formule chimique brute.
* [RDKit](https://github.com/rdkit/rdkit) (**C++ / Python**) – Boîte à outils de référence mondiale en chimio-informatique et modélisation moléculaire.
* [matbench](https://github.com/materialsproject/matbench) (**Python**) – Benchmark standardisé évaluant la performance des modèles ML sur des jeux de données réels de matériaux.

---

## ☁️ Modèles de fondation et initiatives IA

* [Materials Project](https://www.materialsproject.org) – Plateforme ouverte combinant base de données DFT, API REST et outils d'analyse en ligne.
* [GNoME](https://deepmind.google/discover/blog/millions-of-new-materials-discovered-with-deep-learning/) (*Google DeepMind*) – Initiative de découverte à grande échelle ayant prédit la stabilité de plus de 2 millions de cristaux.
* [MatterSim](https://github.com/microsoft/mattersim) (*Microsoft*) – Modèle de fondation pour les simulations atomistiques multi-éléments à température et pression finies.
* [AiiDAlab](https://www.materialscloud.org/aiidalab) – Interface web cloud pour exécuter et partager des flux de calculs AiiDA sans installation locale.
* [Matlantis](https://matlantis.com) – Plateforme commerciale d'accélération de simulations atomistiques par IA.
* [Entalpic](https://entalpic.ai) & [CuspAI](https://www.cusp.ai) – Startups européennes spécialisées dans la conception de matériaux décarbonés par IA générative.
* [Azure Quantum Elements](https://quantum.microsoft.com) – Environnement cloud accélérant la simulation chimique et la DFT par calcul haute performance et IA.

---

## 🗄 Bases de données de matériaux

* [Materials Project](https://www.materialsproject.org) – Propriétés calculées (DFT) de centaines de milliers de composés inorganiques.
* [JARVIS-DFT](https://jarvis.nist.gov/) – Référentiel du NIST contenant des dizaines de milliers de calculs précis, spectres et propriétés électroniques.
* [AFLOWlib](http://www.aflowlib.org) – Dépôt massif de données de structure électronique issues de calculs automatisés à haut débit.
* [COD](https://www.crystallography.net) (*Crystallography Open Database*) – Base libre et participative de structures cristallines expérimentales.
* [ICSD](https://icsd.products.fiz-karlsruhe.de) (_propriétaire_) – Base exhaustive de référence mondiale pour les structures cristallines inorganiques vérifiées.
* [NOMAD](https://nomad-lab.eu) – Grand référentiel FAIR européen pour le partage et l'archivage de calculs atomistiques bruts.
* [OQMD](http://oqmd.org) – *Open Quantum Materials Database*, axée sur les enthalpies de formation et les diagrammes de phases.

---

## 📏 Standards et interopérabilité

* [OPTIMADE](https://www.optimade.org) – Spécification d'API REST unifiée permettant d'interroger plusieurs bases de données de matériaux avec une syntaxe unique.
* [CIF](https://www.iucr.org/resources/cif) – Format de fichier standardisé par l'IUCr pour la description des structures cristallographiques.
* [EMMO](https://github.com/emmo-repo/EMMO) – Ontologie formelle européenne (*European Materials and Modelling Ontology*) structurant les connaissances en physique de la matière.

---

## 🤝 Contribution et Licence

Les propositions d'outils, corrections ou ajouts de ressources sont les bienvenues ! Consultez le fichier [CONTRIBUTING.md](CONTRIBUTING.md) pour connaître les consignes de soumission.

Projet partagé sous licence **[CC0 1.0 (Domaine Public)](https://creativecommons.org/publicdomain/zero/1.0/deed.fr)**.
