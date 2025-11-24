# 🧱 Cub3D — Jeu 3D RayCaster with MiniLibX  

### Projet réalisé en collaboration : [@Hyliah](https://github.com/Hyliah) et [@Melodycherry](https://github.com/Melodycherry) aka *"Les codeuses du dimanche"*
Inspiré du jeu mythique **Wolfenstein 3D** (Id Software, 1992), le premier "First Person Shooter" dans l'histoire du jeu vidéo.  
[Play the original Wolfenstein 3D](http://users.atw.hu/wolf3d/)


## 🎯 Objectifs
Créer une représentation 3D "réaliste" de l’intérieur d’un labyrinthe en **vue à la première personne**, à partir d’un fichier `.cub`.  
Le rendu doit être généré via les principes du **raycasting**, et affiché dans une fenêtre MiniLibX.  


## 🕹️ Règles et Contraintes Principales
• Le rendu doit se faire en **vue subjective (first person)** à l’aide du **raycasting**.  
• Chaque mur doit avoir une **texture différente selon sa direction** (Nord, Sud, Est, Ouest).  
• Le **plafond** et le **sol** doivent avoir chacun une **couleur distincte**.  
• Le programme doit pouvoir :  
  - Afficher l’image dans une fenêtre  
  - Gérer correctement les interactions avec la fenêtre (minimisation, changement de focus, etc.)  
  - Fermer proprement sur `ESC` ou clic sur la croix rouge.  
• Les touches du clavier doivent permettre :  
  - ⬆️ **W** : avancer  
  - ⬇️ **S** : reculer  
  - ⬅️ **A** : se déplacer à gauche  
  - ➡️ **D** : se déplacer à droite  
  - ↩️ **Flèches gauche/droite** : pivoter la caméra  

## 🗺️ Le fichier .cub
Le fichier de map doit contenir :  
- Les **textures** pour chaque direction  
- Les **couleurs du sol et du plafond**
- La **carte du labyrinthe**, composée uniquement des caractères :  
- `1` → mur  
- `0` → espace vide  
- `N`, `S`, `E`, `W`, `D`  → position et orientation du joueur + portes éventuelles    

##  🧱 Exemple de carte valide :  

![Carte](https://github.com/Melodycherry/42-cub3D/blob/main/img_md/screenshot_map.png)

##  ⚠️ Contraintes de la carte :   
- Elle doit être **fermée par des murs**.  
- Les espaces sont **valides** et doivent être gérés correctement.  
- La **map** doit toujours être **le dernier élément du fichier**.  
- En cas d’erreur de configuration, le programme doit afficher un message d'erreur spécifique     

## 🖼️ Graphismes & Fenêtre

### Ecran d'accueil et choix du player :  
![opening](https://github.com/Melodycherry/42-cub3D/blob/main/img_md/opening.png)

### Gameplay et minimap :
![Gameplay](https://github.com/Melodycherry/42-cub3D/blob/main/img_md/gameplay.png)

## ✨ Bonus possibles :  
• 🚪 Collisions avec les murs: OK    
• 🧭 Minimap affichant la position du joueur: OK      
• 🕹️ Portes ouvrables/fermables : OK   
• 🌀 Sprites animés : OK    
• 🖱️ Rotation du point de vue avec la souris : OK      

---

**🧠 Ce que nous avons appris**:  

• 🔦 Principes du **raycasting** pour simuler la 3D à partir d’un plan 2D (Hygie)    
• 🧮 Utilisation des **mathématiques appliquées** pour les angles, distances et projections (Hygie)    
• 🎨 Gestion des **textures** et des **couleurs RGB** avec MiniLibX (Hygie)    
• 🎮 Gestion des **événements clavier** et de la **boucle graphique** (Hygie)    
• 🧱 Parsing complexe d’un fichier `.cub` et validation des cartes (Melo)    
• ❌ Gestion d’erreurs robustes et affichage d’un message clair (Melo)    

---

✅ **STATUT:**  
📅 Date de rendu : -  
📝 Note obtenue : -  

---
