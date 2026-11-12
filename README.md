###### README.md >> markdown 
# InformsLabs

> Une sélection de référence des meilleurs outils, bases de données et plateformes dédiés à l'**informatique des matériaux**
- *Materials Informatics*.

---

## 🔬 Qu'est-ce que l'informatique des matériaux ?

L'**informatique des matériaux** se situe au carrefour de la science des matériaux, de l'intelligence artificielle et de la science des données.
Elle accélère la découverte et la conception de nouveaux matériaux en associant les méthodes de simulation physique (*ab initio*, DFT, dynamique moléculaire) aux approches d'apprentissage automatique (*Machine Learning*).

---

## 📑 Sommaire

- [Logiciels et bibliothèques](#-logiciels-et-bibliothèques)
- [Plateformes Cloud et initiatives IA](#-plateformes-cloud-et-initiatives-ia)
- [Bases de données de matériaux](#-bases-de-données-de-matériaux)
- [Standards et interopérabilité](#-standards-et-interopérabilité)
- [Contribution et Licence](#-contribution-et-licence)

---

## 🛠 Logiciels et bibliothèques

### Simulation & Gestion de flux de calcul (Workflows)
* [AiiDA](http://aiida.net) (**Python**) – Automatisation des calculs *ab initio* et traçabilité des données.
* [ASE](https://wiki.fysik.dtu.dk/ase) (**Python**) – Environnement standard de configuration, manipulation et simulation atomistique.
* [FireWorks](https://materialsproject.github.io/fireworks) & [atomate](https://hackingmaterials.github.io/atomate) (**Python**) – Gestionnaire de tâches et flux de calculs DFT à haut débit.
* [quacc](https://github.com/arosen93/quacc) (**Python**) – Plateforme moderne de calculs haut débit pour la chimie quantique.

### Analyse & Machine Learning appliqué aux matériaux
* [Pymatgen](https://pymatgen.org) (**Python**) – Bibliothèque open source de référence pour l'analyse structurale des matériaux.
* [matminer](https://github.com/hackingmaterials/matminer) (**Python**) – Extraction de caractéristiques (*featurization*) et fouille de données.
* [CDVAE](https://github.com/txie-93/cdvae) (**Python**) – Modèle génératif (VAE à diffusion) pour la conception inverse de structures cristallines.
* [CrabNet](https://github.com/anthony-wang/CrabNet) (**Python**) – Prédiction de propriétés à partir de la seule formule chimique.
* [RDKit](https://github.com/rdkit/rdkit) (**C++ / Python**) – Boîte à outils de référence en chimio-informatique et modélisation moléculaire.
* [matbench](https://github.com/materialsproject/matbench) (**Python**) – Jeux de tests (*benchmarks*) pour les algorithmes prédictifs en science des matériaux.

---

## ☁️ Plateformes Cloud et initiatives IA

* [Materials Project](https://www.materialsproject.org) – Plateforme open-access combinant base de données DFT et outils d'analyse en ligne.
* [AiiDAlab](https://www.materialscloud.org/aiidalab) – Interface web cloud pour exécuter et partager des flux AiiDA.
* [Matlantis](https://matlantis.com) – Plateforme commerciale d'accélération par IA pour la découverte de matériaux.
* [Entalpic](https://entalpic.ai) & [CuspAI](https://www.cusp.ai) – Startups spécialisées dans la découverte de matériaux décarbonés par IA générative.
* [Azure Quantum Elements](https://quantum.microsoft.com) – Environnement Microsoft accélérant la simulation chimique et la DFT via le calcul haute performance et l'IA.

---

## 🗄 Bases de données de matériaux

* [Materials Project](https://www.materialsproject.org) – Propriétés calculées (DFT) de centaines de milliers de composés connus et théoriques.
* [AFLOWlib](http://www.aflowlib.org) – Dépôt massif de données issues de calculs *ab initio* à haut débit.
* [COD](https://www.crystallography.net) (*Crystallography Open Database*) – Base libre de structures cristallines (organiques et inorganiques).
* [ICSD](https://icsd.products.fiz-karlsruhe.de) (_propriétaire_) – Base exhaustive de référence pour les structures cristallines inorganiques.
* [NOMAD](https://nomad-lab.eu) – Grand référentiel européen pour le partage de données brutes issues de calculs atomistiques.
* [OQMD](http://oqmd.org) – *Open Quantum Materials Database*, axée sur la thermodynamique des matériaux.

---

## 📏 Standards et interopérabilité

* [OPTIMADE](https://www.optimade.org) – Spécification d'API REST unifiée pour interroger simultanément plusieurs bases de données de matériaux.
* [CIF](https://www.iucr.org/resources/cif) – Format textuel standardisé (IUCr) pour échanger des descriptions cristallographiques.
* [EMMO](https://github.com/emmo-repo/EMMO) – Ontologie européenne formelle pour la modélisation des matériaux.

---

## 🤝 Contribution et Licence

Les propositions d'outils, corrections ou ajouts de ressources sont les bienvenues ! Consultez le fichier [CONTRIBUTING.md](CONTRIBUTING.md) pour connaître les consignes de soumission.

Projet partagé sous licence **[CC0 1.0 (Domaine Public)](https://creativecommons.org/publicdomain/zero/1.0/deed.fr)**.
