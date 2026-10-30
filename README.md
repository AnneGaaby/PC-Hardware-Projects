# PC Hardware Projects

Projets personnels autour du matériel informatique : configuration et assemblage d'un PC, compréhension des composants, réglages BIOS/UEFI et diagnostic de problèmes matériels ou de stabilité.

**Autrice :** Anne Gabrielly Alves  
**Environnement principal :** Windows 11 · AMD Ryzen · NVIDIA GeForce · DDR5  
**Type de projet :** laboratoire personnel et documentation technique

## Présentation

Ce dépôt présente mon intérêt pour le matériel informatique et les compétences que je développe en assemblage, configuration et dépannage de PC.

Mon PC principal est utilisé pour le développement, les jeux, la virtualisation Linux et l'expérimentation avec des outils d'intelligence artificielle exécutés localement. Cette machine me permet aussi de mieux comprendre les interactions entre processeur, carte mère, mémoire vive, carte graphique, stockage, alimentation, BIOS et pilotes.

Le dépôt documente les composants réellement utilisés et un cas de diagnostic rencontré. Il distingue les actions effectivement tentées des pistes générales de dépannage. Aucun résultat de benchmark ou diagnostic définitif n'est inventé.

## Configuration du PC

| Composant | Modèle |
|---|---|
| CPU | AMD Ryzen 7 9800X3D |
| Carte mère | Gigabyte X870E AORUS ELITE WIFI7 |
| RAM | 64 Go (2 × 32 Go) Kingston FURY Beast RGB DDR5-6000 CL30 |
| GPU | NVIDIA GeForce RTX 5070 Ti Gainward Phoenix |
| SSD | Kingston FURY Renegade G5 NVMe M.2 2280 — 2 To |
| Alimentation | be quiet! Pure Power 12 M — 1000 W |
| BIOS | FA5 |
| Système d'exploitation | Windows 11 |

## Objectifs du dépôt

- Présenter une configuration PC complète et expliquer le rôle de ses composants.
- Documenter les principes de montage et de vérification avant le premier démarrage.
- Comprendre les réglages UEFI/BIOS et les profils mémoire EXPO.
- Apprendre à isoler les problèmes de stabilité et de performances.
- Conserver une trace des essais de dépannage et de leurs résultats.
- Développer des compétences utiles en support informatique et maintenance matérielle.

## Projets et documentation

- [Configuration et composants du PC](docs/PC-BUILD-AND-COMPONENTS.md) — composants, rôles, montage et BIOS.
- [Diagnostic et dépannage](docs/TROUBLESHOOTING.md) — cas de micro-saccades, essais effectués et méthode de diagnostic.

## Cas pratique : micro-saccades et blocages en jeu

Un problème de micro-saccades a été observé pendant certaines sessions de jeu, particulièrement sur l'ancien MMORPG Talisman Online. Les symptômes rapportés comprenaient des chutes brutales de FPS, des blocages temporaires des périphériques et des écrans noirs.

Plusieurs essais ont été effectués : réinstallation et retour à d'anciens pilotes graphiques, mise à jour du BIOS, désactivation de la partie graphique intégrée, comparaison de DirectX 11 et DirectX 12 lorsque possible, modification des paramètres EXPO et contrôle de l'état de santé du SSD.

La cause finale n'est pas confirmée. Le dépôt documente donc les observations et les actions tentées sans prétendre à une résolution qui n'a pas été validée.

## Compétences travaillées

- Identification des composants et compatibilité matérielle.
- Assemblage et maintenance d'un ordinateur.
- Compréhension du BIOS/UEFI.
- Configuration de la mémoire DDR5 et notions d'EXPO.
- Installation et gestion des pilotes sous Windows.
- Diagnostic de problèmes de performances et de stabilité.
- Surveillance des composants et vérification du stockage.
- Documentation technique et démarche de dépannage.

## Méthode de travail

Pour les prochains tests, je souhaite conserver une démarche reproductible :

1. Décrire précisément le symptôme.
2. Relever les versions de BIOS et de pilotes.
3. Mesurer températures, fréquences et performances.
4. Modifier un seul paramètre à la fois.
5. Reproduire le même scénario de test.
6. Noter les résultats et revenir en arrière si nécessaire.
7. Ne conclure qu'à partir de résultats vérifiables.

## À propos

Je suis Anne Gabrielly, basée dans le canton de Vaud, en Suisse, et en formation en développement Web et Web Mobile chez Skill&You Suisse. Je développe également mes compétences en matériel informatique, systèmes, support technique et dépannage.

- **Portfolio :** https://annegaaby.github.io/Anne-Gabrielly/
- **GitHub :** https://github.com/AnneGaaby

---

*Ce dépôt est un portfolio d'apprentissage. Les informations personnelles, clés, identifiants, données privées et configurations sensibles ne doivent pas y être publiés.*
