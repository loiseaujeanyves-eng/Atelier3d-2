# ATELIER 3D — Instructions Codex

Mission : développer une application web mobile-first de conception et impression 3D. Travailler par petites PR vérifiables. Ne jamais prétendre qu'une photo a été analysée si aucun fichier image n'est reçu.

## Parcours prioritaires
1. Initialisation : profil utilisateur, imprimante, matériaux, famille d'objets.
2. Import d'image depuis galerie et appareil photo sur Android/Pixel, avec permissions, erreurs explicites et solution de repli par sélection de fichier.
3. Analyse visuelle : distinguer observations, hypothèses et mesures approximatives; aucune mesure exacte sans référence d'échelle.
4. Atelier de modélisation : primitives, dimensions éditables, transformations, couleurs, aperçu 3D, sauvegarde et historique.
5. Préparation impression : contrôles de géométrie, orientation, dimensions, export STL/3MF selon faisabilité; lancement physique uniquement après validation explicite.

## Qualité et sécurité
- TypeScript strict, tests unitaires et tests E2E mobile, accessibilité et interface française.
- Ne pas inventer de capacités IA ni simuler des services réseau.
- Pas de clé API dans le code, aucune dépense, aucune suppression destructive sans accord.
- Séparer UI, moteur géométrique, stockage, connecteurs et éventuel service IA.
- Documenter limites, preuves de tests, décisions et tâches restantes.

## Première mission Codex
Lire docs/PRODUCT.md et docs/ROADMAP.md. Initialiser une application React + TypeScript + Vite, interface mobile-first, viewer 3D Three.js via React Three Fiber, persistance locale initiale, tests Vitest/Playwright. Livrer un premier parcours testable import photo + atelier primitives + export STL; marquer clairement les fonctions non implémentées. Exécuter build et tests et ouvrir une PR avec résultats.
