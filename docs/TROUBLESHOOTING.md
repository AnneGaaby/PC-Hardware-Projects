# Diagnostic matériel et dépannage

Ce document rassemble un cas réel de diagnostic rencontré sur le PC principal et une méthode générale pour isoler les problèmes de stabilité.

## Configuration concernée

- AMD Ryzen 7 9800X3D
- Gigabyte X870E AORUS ELITE WIFI7
- 64 Go Kingston FURY Beast RGB DDR5-6000 CL30 (2 × 32 Go)
- NVIDIA RTX 5070 Ti Gainward Phoenix
- SSD Kingston FURY Renegade G5 2 To
- Alimentation be quiet! Pure Power 12 M 1000 W
- Windows 11
- BIOS FA5

## Symptômes observés

Pendant des sessions de jeu, notamment sur Fortnite, des micro-saccades et des chutes brutales de fluidité ont été signalées. Certains épisodes étaient accompagnés de chutes de FPS jusqu'à 0, de blocages temporaires des périphériques et d'écrans noirs.

Ces symptômes peuvent avoir plusieurs origines. Ils ne suffisent pas, à eux seuls, à identifier une pièce défectueuse.

## Actions déjà essayées

Les essais rapportés pendant le diagnostic comprennent :

- réinstallation de pilotes graphiques ;
- retour à des versions antérieures de pilotes ;
- mise à jour du BIOS ;
- désactivation de la partie graphique intégrée dans les essais ;
- comparaison de DirectX 11 et DirectX 12 lorsque le jeu le permettait ;
- modification des paramètres mémoire EXPO ;
- contrôle de l'état de santé du SSD, rapporté à 100 %.

Ces essais sont documentés comme des actions tentées. Ils ne prouvent pas qu'une cause précise a été identifiée ni que le problème est définitivement résolu.

## Méthode de diagnostic

### 1. Décrire et reproduire le problème
Noter le jeu ou l'application, la durée avant apparition, les FPS, les températures, les circonstances et les éventuels messages d'erreur. Vérifier si le problème se produit dans plusieurs applications ou seulement dans un jeu.

### 2. Vérifier les journaux Windows
Consulter l'Observateur d'événements et l'historique de fiabilité autour de l'heure du blocage. Rechercher les erreurs système, pilotes, périphériques et arrêts inattendus.

### 3. Contrôler les pilotes
Identifier la version du pilote graphique, vérifier les changements récents et éviter de modifier plusieurs versions ou paramètres à la fois. Comparer les résultats dans les mêmes conditions.

### 4. Contrôler températures et alimentation
Surveiller les températures CPU et GPU, les fréquences et les éventuelles limitations thermiques. Vérifier visuellement les branchements d'alimentation, sans manipuler les composants sous tension.

### 5. Isoler la mémoire
Revenir temporairement à des paramètres mémoire standards, puis effectuer un test de stabilité. Si le comportement change, reprendre les réglages un par un. Ne pas conclure qu'EXPO est responsable sans tests reproductibles.

### 6. Vérifier le stockage
Contrôler l'état SMART, l'espace disponible et les journaux liés au contrôleur ou au stockage. Un état de santé annoncé à 100 % est une indication utile, mais ne permet pas d'exclure toutes les causes de ralentissement.

### 7. Tester progressivement
Reproduire le même scénario après chaque changement et conserver les résultats. Un diagnostic fiable repose sur des comparaisons contrôlées, pas sur plusieurs modifications simultanées.

## Bonnes pratiques

- Sauvegarder les données importantes avant les opérations de maintenance.
- Télécharger les pilotes et BIOS depuis les sites officiels des fabricants.
- Ne pas interrompre une mise à jour du BIOS.
- Éviter les outils d'overclocking multiples en même temps.
- Documenter chaque modification et son résultat.
- Ne pas remplacer un composant avant d'avoir recueilli des éléments suffisants.

## État du diagnostic

Le problème de micro-saccades et de blocages a été observé et plusieurs pistes ont été testées. La cause finale et une résolution définitive ne sont pas confirmées dans les informations disponibles pour ce dépôt.

Ce document sera enrichi lorsque de nouveaux tests reproductibles, journaux ou résultats pourront être ajoutés.
