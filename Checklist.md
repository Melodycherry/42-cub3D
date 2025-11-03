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
- [x] check map valide : entouree de murs
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
- Attention il y a des leaks dans parse_texture. A checker  ( ok done ✓)
- Finir et checker player  ( ok done ✓)
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
- invalid char ✓
- empty line in map ✓
- space and tab before config line ✓
- nothing after the map ✓  ( sauf si empty line et smoth after )
- 
- empty line between config ✓
- no map ✓
- empty map file ✓
- only space or tab in map file ✓
- 
- check too many player on the map ✓
- check with double N N mais aussi avec N + E ou S + W ✓
- check no player on the map ✓  
- 
- pareil pour end map ( car si on met qqchose apres cela fait invalid char et pas nothing after map )
- -> ok regle mais seulement pour la ligne suivant la fin de map. SI qqqch apres, dit invalid char, pas nothing on the map  

- check xpm access ( hygie )  
- check map trop grande ( a partir de combien c'est trop grand )  

*A completer au fur et a mesure* 
