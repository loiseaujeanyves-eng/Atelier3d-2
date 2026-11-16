# ATELIER 3D — cadrage produit initial

Statut : synthèse de travail issue des demandes utilisateur; à rapprocher du cahier des charges v1.2 complet avant de considérer la couverture exhaustive.

## Vision
Application française mobile-first permettant de photographier ou importer un objet, identifier prudemment sa catégorie, proposer une reconstruction 3D vérifiable, modifier un modèle dans un atelier virtuel puis préparer son impression 3D.

## Écrans
- Accueil / initialisation : profil d'impression, machine, matière, catégorie de produits.
- Capture / import : appareil photo et galerie, aides Android aux permissions, erreurs et formats.
- Atelier : scène 3D interactive, outils de création et d'édition, palette chaleureuse et épurée, changement de couleur, dimensions et sauvegarde.
- Bibliothèque : projets, versions, modèles et sources avec provenance et droits.
- Préparation impression : contrôles, aperçu et exports.

## Exigences critiques
- Le bouton photo doit réellement ouvrir la caméra ou un choix de fichier selon le navigateur; prévoir input capture et input file séparés et un fallback documenté.
- Une seule photo ne fournit pas une géométrie ou des dimensions fiables : afficher des hypothèses et demander une cote de référence.
- Rechercher documentation fabricant et plans techniques lorsque la recherche est réellement disponible; enregistrer les sources.
- Ne pas confondre visualisation 3D, reconstruction automatique et fichier imprimable.
- Respecter licences, confidentialité des photos, sécurité des fichiers et consentement avant envoi externe.

## Experts / revues
AMOA, architecte logiciel, UX mobile/accessibilité, développeur front-end, expert CAO/géométrie, spécialiste vision IA, expert impression 3D/slicing, QA automatisation, sécurité et licences, DevOps. Chaque revue produit une décision et une preuve, sans prétendre simuler des personnes réelles.
