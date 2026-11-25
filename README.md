# Ondine

Des visuels qui réagissent à ta musique en direct.

**Lien :** https://hydra-v-ion.github.io/Ondine/

> Projet vibecodé : l'application a été écrite avec l'aide d'une IA (Claude), à partir d'idées et d'itérations successives.

## Fonctionnalités

- **25 scènes** : fractales (Mandelbulb, Burning Ship), motifs, ondes, néon, synthwave, méduse, etc.
- **12 palettes** de couleurs, dont une palette personnalisable.
- **Une scène « image perso »** : charge ta propre image ou vidéo.
- **Analyse audio ciblée** : choisis la plage de fréquences à suivre (basses, kicks, aigus) et règle la sensibilité des kicks.
- **Trois sources** : un fichier audio, le micro, ou l'audio d'un onglet.
- **Éditeur de nœuds** : relie des cartes entre elles pour composer tes propres visuels (générateurs, effets, sortie). Les effets incluent le glitch, l'ASCII (six jeux de caractères, dont kanas), le contraste noir et blanc, les miroirs et le flou.
- **Séquenceur et cartes de signal** : tempo, compteur, aléatoire, souris, etc., pour animer ce que tu crées.
- **Enregistrement vidéo** (format mp4 lisible sur téléphone).
- **Sauvegarde automatique** de ton graphe dans le navigateur, et export/import en JSON.

## Utilisation

1. Ouvre la page et choisis une source : **♪ Fichier**, **🎤 Micro** ou **🖥 Onglet**.
2. Change de scène et de palette depuis le panneau.
3. Pour composer tes visuels, ouvre **🕸 Éditeur de nœuds** et utilise **＋ Ajouter**.

### Raccourcis

| Touche | Action |
| --- | --- |
| `1` à `0`, `q` `w` `e` `r` `t` `y` `u` `i` `o` `j` `k` `l` `z` `x` `c` | Choisir une scène |
| `←` / `→` | Scène précédente / suivante |
| `p` | Palette suivante |
| `h` | Masquer / afficher le panneau |
| `f` | Plein écran |
| `g` | Afficher / masquer l'éditeur de nœuds |
| `Espace` | Lecture / pause (fichier audio) |

Dans l'éditeur : `Suppr` supprime la sélection, `Ctrl+D` duplique, `Ctrl+A` sélectionne tout, double-clic sur un fil le coupe.

## Lancer en local

Le projet est un seul fichier `index.html`. Ouvre-le simplement dans un navigateur récent (Chrome, Edge, Firefox ou Safari). Un ordinateur avec WebGL 2 est nécessaire.

## Limites connues

- L'analyse de l'audio est un peu capricieuse ; il est parfois difficile de faire réagir correctement un visuel.
- Certains navigateurs mobiles peuvent limiter l'enregistrement ou la capture d'onglet.
