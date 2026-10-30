# Configuration du PC — montage et composants

Ce document présente la configuration matérielle de mon PC principal, utilisée pour le développement, les tests, les jeux et l'expérimentation avec des outils d'intelligence artificielle en local.

## Configuration

| Composant | Modèle |
|---|---|
| Processeur | AMD Ryzen 7 9800X3D |
| Carte mère | Gigabyte X870E AORUS ELITE WIFI7 |
| Mémoire vive | 64 Go (2 × 32 Go) Kingston FURY Beast RGB DDR5-6000 CL30 |
| Carte graphique | NVIDIA GeForce RTX 5070 Ti Gainward Phoenix |
| Stockage | Kingston FURY Renegade G5 NVMe M.2 2280 — 2 To |
| Alimentation | be quiet! Pure Power 12 M — 1000 W |
| BIOS | Version FA5 |
| Système | Windows 11 |

Les références ci-dessus correspondent aux composants et à la configuration communiqués pour ce projet. Les fréquences réellement appliquées, températures, benchmarks et résultats de stabilité ne sont pas publiés ici faute de mesures documentées.

## Pourquoi cette configuration ?

Ce PC sert à plusieurs usages :
- développement web et programmation ;
- assemblage et découverte du matériel informatique ;
- jeux vidéo, notamment des titres anciens ;
- virtualisation et administration de machines Linux ;
- expérimentation avec des modèles d'IA exécutés localement.

La configuration associe un processeur AMD Ryzen, une carte mère à plateforme AM5, de la mémoire DDR5, une carte graphique NVIDIA récente et un SSD NVMe.

## Comprendre les composants

### Processeur (CPU)
Le processeur exécute les instructions des programmes et coordonne une grande partie des opérations du système. Le Ryzen 7 9800X3D est le CPU installé dans cette machine.

### Carte mère
La Gigabyte X870E AORUS ELITE WIFI7 accueille le processeur, la mémoire, la carte graphique et les périphériques. Elle assure les communications entre ces composants et fournit les réglages du firmware UEFI/BIOS.

### Mémoire vive (RAM)
La machine dispose de 64 Go de DDR5, sous la forme de deux modules de 32 Go. La mémoire vive conserve temporairement les données utilisées par les applications. Le kit est spécifié DDR5-6000 CL30 ; la fréquence effective dépend des paramètres du BIOS et de la stabilité de la plateforme.

### Carte graphique (GPU)
La RTX 5070 Ti Gainward Phoenix accélère les traitements graphiques et peut également être utilisée par des applications compatibles avec le calcul GPU, notamment certains outils d'IA locaux.

### Stockage
Le Kingston FURY Renegade G5 est un SSD NVMe au format M.2 2280 de 2 To. Il accueille le système et les applications. La santé du SSD avait été rapportée à 100 % lors d'un contrôle effectué pendant les diagnostics.

### Alimentation
L'alimentation be quiet! Pure Power 12 M de 1000 W fournit l'énergie aux composants. La puissance nominale seule ne garantit pas qu'un système soit stable : câblage, branchements, températures et état des composants comptent également.

## Montage : méthode générale

Le montage d'un PC doit être effectué hors tension, avec une attention particulière à l'électricité statique et aux consignes des fabricants.

1. Préparer un espace propre, stable et dégagé.
2. Vérifier la compatibilité du processeur avec le socket de la carte mère.
3. Installer le processeur en respectant le repère du socket, sans forcer.
4. Installer la mémoire dans les emplacements recommandés par le manuel de la carte mère.
5. Installer le SSD M.2 et son dissipateur, si nécessaire.
6. Fixer la carte mère dans le boîtier avec les entretoises appropriées.
7. Installer le refroidissement du processeur et vérifier son branchement.
8. Installer la carte graphique dans le port PCIe adapté et la fixer au boîtier.
9. Brancher l'alimentation de la carte mère, du processeur, de la carte graphique et des périphériques.
10. Vérifier tous les branchements avant le premier démarrage.
11. Accéder à l'UEFI/BIOS, vérifier la détection du matériel et surveiller les températures.
12. Installer le système d'exploitation, les pilotes et les outils de diagnostic.

Cette liste est une procédure générale de référence, pas un journal photographique détaillé de chaque étape du montage de cette machine.

## BIOS et mémoire

La version de BIOS communiquée pour cette configuration est FA5. Le profil mémoire EXPO et les paramètres de fréquence ont été modifiés pendant les essais de diagnostic des micro-saccades.

EXPO permet d'appliquer un profil mémoire contenant des paramètres plus élevés que les réglages de base JEDEC. Son activation doit être suivie de tests de stabilité. Un système qui démarre n'est pas nécessairement stable dans toutes les charges.

Bonnes pratiques :
- noter les réglages avant de les modifier ;
- ne changer qu'un paramètre à la fois ;
- vérifier la stabilité après chaque changement ;
- éviter de charger plusieurs profils ou réglages simultanément pendant un diagnostic ;
- consulter le manuel de la carte mère et les recommandations des fabricants.

## Pistes de validation à documenter

Pour compléter le dossier avec des mesures reproductibles, il serait utile d'ajouter :
- captures de l'UEFI montrant la version du BIOS et la mémoire détectée ;
- températures CPU/GPU au repos et en charge ;
- fréquence mémoire réellement appliquée ;
- résultats d'un test mémoire ;
- résultats de benchmarks CPU, GPU et stockage ;
- photos du montage et de l'intérieur du boîtier.

Aucun score de benchmark ni aucune température ne sont inventés dans ce document.
