# Jeux Marty

Petite appli Android avec deux jeux :

- 🟢 **Boutons Pressés** : touche les boutons verts qui tombent avant qu'ils sortent en bas… mais surtout pas les rouges ! 1 minute, et ça accélère.
- 🔤 **Mot Flash** : un carré révèle un à un les mots cachés d'une grille. Quand il s'arrête, tape le dernier mot affiché ! 10 niveaux, de 1 à 3 mots par seconde, sur une grille qui s'allonge jusqu'à 6 lignes.

## 📲 Télécharger

**[Télécharger l'APK (Android)](https://github.com/martin12carrier-alt/boutons-presses/releases/latest/download/boutons-presses.apk)**

Ou scanne ce QR code avec ton téléphone :

<img src="qr-telechargement.png" alt="QR code de téléchargement" width="240" />

## Installation

1. Ouvre le lien (ou scanne le QR code) sur ton téléphone Android.
2. Ouvre le fichier `boutons-presses.apk` téléchargé.
3. Autorise l'installation depuis ton navigateur si Android le demande.
4. Si Play Protect affiche un avertissement, choisis « Installer quand même » (l'appli ne vient pas du Play Store).

## Règles de Boutons Pressés

- 🟢 **+10** par bouton vert touché, multiplié par le combo (x2 tous les 5 touchés d'affilée, jusqu'à x4)
- 🔴 **−10** si tu touches un bouton rouge (laisse-les passer, ça ne coûte rien)
- **−5** par bouton vert raté
- **−2** pour un toucher dans le vide
- Bats ton record !

## Règles de Mot Flash

- Chaque case de la grille cache un mot
- Un carré passe sur les cases dans l'ordre (de gauche à droite, de haut en bas) et révèle les mots
- À chaque nouveau passage sur une case, le mot change
- Au bout de 5 à 20 secondes (au hasard), il s'arrête et tout se cache : tape le dernier mot affiché
- 10 niveaux : 1 mot par seconde au niveau 1, jusqu'à 3 mots par seconde au niveau 10
- La grille a 3 colonnes et s'allonge : 3 lignes, puis 4 au niveau 3, 5 au niveau 6 et 6 au niveau 9
- Dans une grille, les mots ont tous à peu près la même longueur (2 lettres d'écart au maximum)
- Niveau raté ? Tu le rejoues avec de nouveaux mots. Accents et majuscules ne comptent pas.
