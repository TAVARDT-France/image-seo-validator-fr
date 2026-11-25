# Analyseur de SEO d'Images et d'Accessibilite Visuelle

[![Analyseur SEO Images](https://img.shields.io/badge/TAVARDT-Image%20SEO-5b3cf5.svg)](https://tools.tavardt.com/fr/analyseur-seo-images/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Audit des balises alt, formats de nouvelle generation (WebP/AVIF) et dimensions pour la stabilite visuelle.

Developpe et maintenu par la division d'architecture semantique et d'accessibilite de **TAVARDT**.

***

## Capacites d'Audit de SEO pour les Images

* **Controle des Balises Alt et Accessibilite**: Verification de la presence et de la pertinence des attributs `alt` sur l'ensemble des elements visuels.
* **Adoption des Formats de Nouvelle Generation**: Controle de l'utilisation des formats WebP et AVIF pour reduire le poids des pages.
* **Stabilite Visuelle et Prevention du CLS**: Verification des dimensions explicites `width` et `height`.
* **Chargement Differe (Lazy Loading)**: Audit de l'activation de `loading="lazy"` sur les images hors ecran.
* **Score d'Optimisation des Images**: Note technique de 0 a 100 avec synthese des recommandations.

***

## Installation et Execution

Necessite Python 3.8 ou superieur, sans dependances tierces.

```bash
git clone https://github.com/TAVARDT-France/image-seo-validator-fr.git
cd image-seo-validator-fr
python image_seo_validator.py https://entreprise.fr
```

Pour generer un rapport au format structure JSON:

```bash
python image_seo_validator.py https://entreprise.fr -json
```

***

## Diagnostic Complet sur le Web

Pour les analyses approfondies de ressources graphiques:

* **Analyseur de SEO pour Images Officiel**
* **[Portail Entreprise TAVARDT](https://ag.tavardt.com/fr/)**

***

## Conseil en Accessibilite Visuelle et Performance

Pour securiser vos catalogues d'images conformement aux normes Normes W3C RGAA et Recommandations SEO, contactez l'equipe de **TAVARDT**.

***

## Liens Utiles

* **Portail Entreprise:** https://ag.tavardt.com/fr/
* **Suite de Diagnostic:** https://tools.tavardt.com/fr/
* **Contact Technique:** https://ag.tavardt.com/fr/contact/

***

### Licence
Distribué sous la Licence MIT. Consultez le fichier [LICENSE](LICENSE) pour plus de détails.

***

© 2026 TAVARDT. Tous droits réservés.
