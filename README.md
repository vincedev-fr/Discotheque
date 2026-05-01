# 🎵 JukeBox TimeMachine

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow)
![YouTube API](https://img.shields.io/badge/YouTube-IFrame%20API-red)

> Un lecteur musical rétro-futuriste qui voyage dans le temps grâce à YouTube

## ✨ Fonctionnalités

### 🎮 Lecteur principal
- Lecture vidéo YouTube intégrée (ratio 16/9)
- Contrôles : précédent, suivant, lecture automatique, répétition, mode aléatoire
- Affichage en temps réel du titre, artiste et année
- Indicateur visuel de lecture (pastille animée)

### 📋 Playlist dynamique
- Liste numérotée des titres à lire
- Suppression individuelle par croix
- Sauvegarde automatique dans `localStorage`
- Import/Export en CSV
- Persistance au rechargement de la page

### 🔍 Recherche et filtres avancés
- **Filtres :**
  - Artiste / Titre (recherche texte)
  - Plage d'années (avec exclusion automatique des dates inconnues)
  - Note minimale (système étoiles ★★★)
  - Album original
- **Tri** possible sur toutes les colonnes (clic sur en-tête)
- **Bouton "Tout ajouter"** pour transférer rapidement les résultats vers la playlist

### 💾 Gestion des données
- Base musicale au format CSV/JSON (9 champs)
- Import/export complet de la bibliothèque
- Jeu de données par défaut inclus (30+ titres des années 70-90)
- Parsing flexible : support CSV et JSON

### 🎨 Interface utilisateur
- Design sombre et néon (cyberpunk / rétro)
- Polices personnalisées (Bebas Neue, Playfair Display, IBM Plex Mono)
- Disposition responsive (masquage dynamique des filtres)
- Notifications temporaires en bas à droite
- Zone de lecture et playlist redimensionnées automatiquement

## 🚀 Installation

1. **Cloner le dépôt**
```bash
git clone https://github.com/votre-username/jukebox-timemachine.git
cd jukebox-timemachine