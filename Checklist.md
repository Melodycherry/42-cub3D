# CHECKLIST

- [ ] Chose à faire
- [x] Chose déjà faite

### ARCHITECTURE
- [x] libft
- [x] Istaller minilibx
- [x] Structures : player
- [x] Structures : map
- [x] Structures : game ( graphic ?)
- [x] Structures : colors / direction ( settings ? )

### MAPS
- [x] maps exemple
- [x] maps simples
- [x] maps complexes
- [ ] plusieurs map avec erreurs ( modif seront faites directement en correction )

### PARSING

- [x] check arg
- [x] check extension .cub
- [x] check file access
- [x] Parse_file a faire
- [x] check presence de toutes les textures NO, SO, WE, EA
- [x] check les couleurs ( entre 0 - 255)
- [x] check player
- [x] check map valide : entouree de murs
- [x] check map valide : invalid caracteres ( pas : 0, 1, N, S, E, W)
- [x] flood fill a faire tout a la fin a partir de position du joueur 

### WINDOWS

- [x] Init MLX
- [x] creer fenetres
- [x] charger les textures (mlx_xpm_file_to_image)
- [x] gerer fermeture fenetre ( ESC + la croix )

### Raycasting

** still don't know what to put here ** Hygie is doing it

### GAME

- [x] player avec touche W A S D
- [x] mise a jour de position du joueur
- [x] gerer colision avec les murs 


### Vrac

- [x] fonction pour quitter proprement
- [x] fonction pour messages d'erreurs personnalises

Pense bete :
- faire refacto des dernieres fonctions trop longues ( ok done ✓)
- Attention il y a des leaks dans parse_texture. A checker  ( ok done ✓)
- Finir et checker player  ( ok done ✓)
- Flood fill at the end ( Merci Hygie )


# RECAP DE TESTS A FAIRE

- [x] no arg ✓
- [x] wrong extension ✓
- 
- [x] invalid texture format ✓
- [x] missing texture ✓
- [x] duplicate texture orientation ✓
- [x] texture already defined ✓
- 
- [x] missing floor or ceiling ✓
- [x] duplicate floor or ceiling ✓
- [x] invalid color ( 0 - 255 ) ✓
- [x] invalid color ID ( F - C ) ✓
- [x] invalid rgb format ✓
- [x] spaces between digits ✓
- [x] rgb component missing ✓
- 
- [x] invalid char ✓
- [x] empty line in map ✓
- [x] space and tab before config line ✓
- [x] nothing after the map ✓  
- 
- [x] empty line between config ✓
- [x] no map ✓
- [x] empty map file ✓
- [x] only space or tab in map file ✓
- 
- [x] check too many player on the map ✓
- [x] check with double N N mais aussi avec N + E ou S + W ✓
- [x] check no player on the map ✓
-
- [x] map not enclosed with wall ✓  


