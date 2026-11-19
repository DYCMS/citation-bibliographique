# Citation HEG

Petit générateur autonome de références bibliographiques basé sur le *Guide de rédaction des références bibliographiques* de la Bibliothèque de la HEG Genève (version 5.3.2), qui suit le système auteur-date fondé sur ISO 690.

## Fonctionnalités

- Reconnaissance indicative du type de document à partir d’une description en langage naturel.
- Formulaires modifiables pour les articles, entrées d’encyclopédie, brevets, contributions de conférence, livres, chapitres, pages web, rapports, données, logiciels, présentations, travaux de diplôme, émissions, enregistrements audio/vidéo et textes juridiques.
- Aperçu de la référence complète et de l’appel de citation dans le texte.
- Bibliographie classée par ordre alphabétique, mémorisée localement, copiable ou téléchargeable.
- Aucune dépendance, aucun compte et aucune donnée envoyée à un serveur.

L’analyse du texte libre utilise des règles locales simples. Elle n’interroge pas le web et ne vérifie pas les métadonnées. Les références doivent être contrôlées à partir de la source originale. Les règles et modèles peuvent évoluer : comparer le résultat à la version du guide demandée par son établissement.

## Utilisation

Ouvrir `index.html` dans un navigateur. Une connexion internet n’est pas nécessaire.

## Publication avec GitHub Pages

Le dépôt doit être créé sur GitHub, puis ces fichiers ajoutés à sa branche `main`. Le workflow `.github/workflows/pages.yml` publie le site à chaque mise à jour de cette branche. Dans les paramètres du dépôt, choisir **Settings → Pages → Build and deployment → Source → GitHub Actions**. L’adresse du site apparaîtra ensuite dans cette même section.

## Base documentaire

Bibliothèque de la Haute école de gestion de Genève, *Guide de rédaction des références bibliographiques*, version 5.3.2, notamment les modèles de sources (pp. 6–27) et le système auteur-date (pp. 33–38). Le guide indique que sa mise à disposition est sous licence Creative Commons Attribution – Pas d’Utilisation Commerciale – Partage dans les Mêmes Conditions 4.0 International. Ce projet n’est pas un service officiel de la HEG.
