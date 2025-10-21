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
- [ ] maps simples
- [ ] maps complexes
- [ ] plusieurs map avec erreurs

### PARSING

- [x] check arg
- [x] check extension .cub
- [x] check file access
- [x] Parse_file a faire
- [x] check presence de toutes les textures NO, SO, WE, EA
- [x] check les couleurs ( entre 0 - 255)
- [x] check player
- [ ] check map valide : entouree de murs
- [x] check map valide : invalid caracteres ( pas : 0, 1, N, S, E, W)
- [ ] flood fill a faire tout a la fin a partir de position du joueur 

### WINDOWS

- [x] Init MLX
- [x] creer fenetres
- [ ] charger les textures (mlx_xpm_file_to_image)
- [ ] gerer fermeture fenetre ( ESC + la croix )

### Raycasting

** still don't know what to put here ** Hygie is doing it

### GAME

- [ ] player avec touche W A S D
- [ ] mise a jour de position du joueur
- [ ] gerer colision avec les murs 


### Vrac

- [x] fonction pour quitter proprement
- [x] fonction pour messages d'erreurs personnalises

Pense bete :
- faire refacto des dernieres fonctions trop longues ( ok done ✓)
- Attention il y a des leaks dans parse_texture. A checker
- Finir et checker player
- Flood fill at the end 

### Recap de tests a faire 
- no arg ✓
- wrong extension ✓
- 
- invalid texture format ✓
- missing texture ✓
- duplicate texture orientation ✓
- texture already defined ✓
- 
- missing floor or ceiling ✓
- duplicate floor or ceiling ✓
- invalid color ( 0 - 255 ) ✓
- invalid color ID ( F - C ) ✓
- invalid rgb format ✓
- spaces between digits ✓
- rgb component missing ✓
- 
- invalid char !!! marche plus ---------------------------------------------------
- empty line in map !!!! ne marche plus ------------------------------------------
- space and tab before config line !!! ne marche plus ------------------------------------------
- nothing after the map ✓
- 
- empty line between config ✓
- no map ✓
- empty map file ✓
- only space or tab in map file ✓



*A completer au fur et a mesure* 
