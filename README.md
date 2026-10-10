# 🎮 Roblox Hobby Map - 500 Niveaux

Une map Roblox amusante et colorée avec **500 niveaux progressifs** du plus facile au plus extrême! Parfait pour jouer entre amis.

## 📋 Caractéristiques

✅ **500 niveaux** avec difficulté progressive (Simple → Moyen → Difficile → Extrême)
✅ **Respawns** personnalisés pour chaque niveau
✅ **Obstacles variés** inspirés des hobbies populaires:
   - Platforming & Parkour
   - Sauts de précision
   - Obstacles en rotation
   - Lasers et barrières
   - Sections de surf/glisse
   - Mines/explosions
   - Murs mouvants
   - Pièges temporisés
   - Passages étroits

✅ **Système de célébration** : Confettis + Message de félicitation à la fin
✅ **Checkpoints** à chaque niveau pour progression rapide
✅ **Système de couleurs** dynamique (chaque zone = couleur unique)
✅ **Leaderboard** optionnel avec temps de completion

## 🎨 Design des Niveaux

### Zones de Difficulté:
- **Niveaux 1-100** : Simple (Bleu)
- **Niveaux 101-250** : Moyen (Vert)
- **Niveaux 251-400** : Difficile (Orange/Rouge)
- **Niveaux 401-500** : Extrême (Pourpre/Rose)

## 📁 Structure du Projet

```
roblox-hobby-map/
├── README.md
├── INSTALLATION.md
├── OBSTACLES.md
├── scripts/
│   ├── MainManager.lua          # Script principal du hobby
│   ├── LevelManager.lua         # Gestion des niveaux
│   ├── ObstacleGenerator.lua    # Génération des obstacles
│   ├── PlayerProgress.lua       # Suivi progression joueur
│   ├── CelebrationEffects.lua   # Confettis et animations
│   └── CheckpointSystem.lua     # Système de checkpoints
├── levels/
│   ├── levels_1_100.lua         # Niveaux simples
│   ├── levels_101_250.lua       # Niveaux moyens
│   ├── levels_251_400.lua       # Niveaux difficiles
│   └── levels_401_500.lua       # Niveaux extrêmes
└── config/
    ├── colors.lua               # Configuration des couleurs
    ├── obstacles.lua            # Types d'obstacles
    └── settings.lua             # Paramètres globaux
```

## 🚀 Installation Rapide

1. Ouvre **Roblox Studio**
2. Crée un nouveau **Baseplate** (plan de base)
3. Copie les scripts dans **ServerScriptService**
4. Configure les obstacles dans les fichiers de config
5. Teste sur ton serveur!

## 🎯 Comment Ça Marche

1. Le joueur spawn au niveau 1
2. Chaque niveau a son propre checkpoint de respawn
3. À chaque fin de niveau, progression automatique
4. Les obstacles deviennent progressivement plus durs
5. À la fin (niveau 500): **Confettis + Message de félicitation!**

## 🎪 Types d'Obstacles

- 🟦 Platformes instables
- 🔄 Obstacles rotatifs
- ⚡ Lasers mobiles
- 🌊 Sections de surf
- 💣 Mines/Pièges explosifs
- 🧱 Murs mouvants
- ⏱️ Défis temporisés
- 🕳️ Passages ultra-étroits
- 🪀 Pendules géants
- 🎡 Roues tournantes

## 📊 Progression de Difficulté

| Zone | Niveaux | Difficulté | Couleur | Thème |
|------|---------|-----------|--------|-------|
| Débutant | 1-100 | ⭐ | 🔵 Bleu | Platforming basique |
| Intermédiaire | 101-250 | ⭐⭐⭐ | 🟢 Vert | Parkour & Obstacles |
| Avancé | 251-400 | ⭐⭐⭐⭐ | 🟠 Orange | Challenges intenses |
| Expert | 401-500 | ⭐⭐⭐⭐⭐ | 🟣 Pourpre | Mode Extrême |

## 🏆 Accomplissements

- ✅ Terminer 100 niveaux
- ✅ Terminer 250 niveaux
- ✅ Terminer 400 niveaux
- 🎉 **Terminer les 500 niveaux** → Badge spécial!

## 🎮 Commandes

- **Espace** : Sauter
- **ZQSD/WASD** : Se déplacer
- **R** : Respawn au checkpoint
- **Souris** : Caméra

## 💡 Conseils pour les Joueurs

- Pratiquez chaque niveau avant de progresser
- Utilisez les checkpoints intelligemment
- Les niveaux extrêmes demandent de la précision et du timing
- Jouez avec des amis pour plus de plaisir!

---

**Amusez-vous bien! 🎉**
