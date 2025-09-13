# 🚀 Fency in Univers

Un jeu de vaisseau spatial moderne développé en HTML5/JavaScript avec des graphiques 2D avancés et une physique réaliste.

## 🎮 Aperçu du Jeu

![Screenshot 1](Capture%20d'écran%202025-09-13%20214126.png)

**Fency in Univers** offre une expérience de combat spatial immersive avec :
- **Contrôles fluides** au clavier et à la souris
- **Système de combat** avec projectiles et ennemis variés
- **Minimap circulaire** pour la navigation
- **Effets visuels** et explosions
- **Système de progression** avec différents types d'ennemis

![Screenshot 2](Capture%20d'écran%202025-09-13%20214146.png)

## 🎥 Démonstration Vidéo

[![Gameplay Video](Capture%20d'écran%202025-09-13%20214126.png)](Enregistrement%202025-09-13%20214043.mp4)

*Cliquez sur l'image pour voir la vidéo de gameplay*

## 🎯 Fonctionnalités

### ✨ Gameplay
- **Monde ouvert** avec caméra qui suit le vaisseau
- **12 types d'ennemis** différents avec des caractéristiques uniques
- **Système de tir** avec projectiles du joueur et des ennemis
- **Collisions réalistes** et système de dégâts
- **Barre de vie** et système de santé
- **Score** basé sur les ennemis détruits

### 🎮 Contrôles
#### Clavier
- `Z` ou `↑` - Avancer
- `Q` ou `←` - Tourner à gauche  
- `D` ou `→` - Tourner à droite
- `S` ou `↓` - Freiner
- `Espace` - Tirer

#### Souris
- `M` - Activer/désactiver le contrôle à la souris
- Déplacer la souris - Orienter le vaisseau
- Clic gauche - Tirer

### 🤖 Ennemis
Le jeu propose 12 types d'ennemis avec des caractéristiques progressives :

| Type | Couleur | Dégâts | Rayon | Vie | Score | Cadence de Tir |
|------|---------|--------|-------|-----|-------|----------------|
| 1 | Rouge | 5 | 15px | 40 | 5 pts | Lente |
| 2 | Bleu | 10 | 20px | 60 | 10 pts | Rapide |
| 3 | Vert | 15 | 25px | 80 | 15 pts | Rapide |
| 4 | Jaune | 20 | 30px | 100 | 20 pts | Rapide |
| 5 | Violet | 30 | 35px | 130 | 30 pts | Très rapide |
| 6 | Corail | 40 | 40px | 150 | 50 pts | Ultra rapide |
| 7 | Orange | 50 | 45px | 200 | 100 pts | Ultra rapide |
| 8 | Rose | 60 | 50px | 250 | 150 pts | Lente |
| 9 | Cyan | 60 | 55px | 300 | 200 pts | Rapide |
| 10 | Lime | 70 | 60px | 350 | 250 pts | Très rapide |
| 11 | Magenta | 86 | 65px | 400 | 300 pts | Ultra rapide |
| 12 | Blanc | 88 | 70px | 500 | 500 pts | Lente |

## 🛠️ Technologies Utilisées

- **HTML5 Canvas** - Rendu graphique 2D
- **JavaScript ES6+** - Logique de jeu et animations
- **CSS3** - Interface utilisateur et styling
- **Programmation orientée objet** - Architecture modulaire

## 📁 Structure du Projet

```
fency-in-univers/
├── fency 0.1.1.html          # Version finale du jeu
├── fency 0.1.0.html          # Version précédente
├── fency 0.0.x.html          # Versions de développement
├── Capture d'écran *.png     # Screenshots du jeu
├── Enregistrement *.mp4      # Vidéo de démonstration
└── README.md                 # Ce fichier
```

## 🚀 Comment Jouer

1. **Ouvrir le jeu** : Lancez `fency 0.1.1.html` dans votre navigateur web
2. **Contrôles** : Utilisez les touches ZQSD ou les flèches directionnelles
3. **Objectif** : Détruisez les ennemis pour gagner des points
4. **Survie** : Évitez les projectiles ennemis et les collisions
5. **Progression** : Affrontez des ennemis de plus en plus puissants

## 🎨 Caractéristiques Techniques

### Physique du Jeu
- **Système de mouvement** avec accélération et décélération
- **Rotation progressive** du vaisseau
- **Détection de collisions** circulaires
- **Système de répulsion** pour éviter les chevauchements

### Graphiques
- **Rendu en temps réel** à 60 FPS
- **Effets de particules** pour les explosions
- **Animations fluides** des sprites
- **Interface utilisateur** responsive

### Intelligence Artificielle
- **IA des ennemis** avec comportement de poursuite
- **Évitement de collisions** entre ennemis
- **Système de tir** intelligent basé sur la distance
- **Spawn aléatoire** des ennemis autour du joueur

## 🔧 Développement

### Versions
- **v0.0.1** - Prototype initial avec vaisseau de base
- **v0.0.5** - Ajout des ennemis et système de combat
- **v0.1.0** - Implémentation de la minimap et améliorations UI
- **v0.1.1** - Version finale avec tous les systèmes optimisés

### Améliorations Futures
- [ ] Système de power-ups
- [ ] Niveaux avec boss
- [ ] Multijoueur local
- [ ] Effets sonores
- [ ] Sauvegarde des scores

## 📊 Statistiques du Projet

- **Lignes de code** : ~1700 lignes JavaScript
- **Types d'ennemis** : 12 variantes
- **Système de contrôle** : Clavier + Souris
- **Compatibilité** : Tous navigateurs modernes

## 🏆 Crédits

Développé avec passion pour créer une expérience de jeu spatial immersive et addictive.

---

*Amusez-vous bien et que la force soit avec vous dans l'espace ! 🌌*
